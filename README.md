# coffee-hexa-simple

A small coffee catalog REST API (coffees and their reviews) built with hexagonal architecture: the domain and application layers are plain Java, and REST, JPA and transactions live in adapters.

## Run

```bash
./mvnw spring-boot:run
```

Swagger UI: http://localhost:8080/swagger-ui/index.html

## Screenshots

Swagger UI:

![Swagger UI](docs/screenshots/11-swagger-ui.png)

List of coffees:

![GET /api/coffees](docs/screenshots/04-get-coffees.png)

Unknown coffee (404 problem details):

![404](docs/screenshots/05-not-found-404.png)

H2 console after a POST and a `PATCH {"price":12}`:

![H2 console](docs/screenshots/12-h2-console.png)

Health check:

![Health](docs/screenshots/13-health.png)
