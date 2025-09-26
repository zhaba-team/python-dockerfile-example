# python-dockerfile-example

Репозиторий для демонстрации сборки Docker-образа из Dockerfile и деплоя проекта на Python с фреймворком FastAPI

```bash
docker build -t python-dockerfile-example .
docker run -d -p 8000:8000 python-dockerfile-example
```