# Cache Testing

## Prerequisite

Need to install Docker and Docker-Compose At First.

## Usage

start server:

```bash
docker-compose up
```

reload nginx config:

```bash
docker-compose exec static-server nginx -s reload
```

> nginx log is saved in log folder
