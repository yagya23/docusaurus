# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Create a dockerfile


```
docker build . -t docu:1.1

```

### Run Dockerfile

```
docker run -d  -p 80:3000 docu:1.1

```

### Access URL

```
http://localhost/

```
