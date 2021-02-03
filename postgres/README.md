# Postgres

## adminer

Launch postgres and adminer

adminer command is alias for `docker-compose -f docker-compose.yml -f docker-compose.adminer.yml`

```bash
./adminer up
```

Access to [localhost:8080](http://localhost:8080)

- Database Type: `PostgreSQL`
- Server: `db`
- Username: `postgres`
- Password: `password`
- Database: `postgres`

## pgadmin4

Launch postgres and pgadmin4

pgadmin4 command is alias for `docker-compose -f docker-compose.yml -f docker-compose.pgadmin4.yml`

```bash
./pgadmin4 up
```

Access to [localhost:8080](http://localhost:8080)

- email: `admin@example.com`
- password: `password`
