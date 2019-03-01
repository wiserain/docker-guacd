## DEPRECATED

It is suggested adding custom fonts by bind-mount of folders:

```yaml
version: '3.5'

services:
  guacd:
    image: guacamole/guacd
    container_name: guacd
    volumes:
      - "${DOCKER_ROOT}/guacamole/D2Coding:/usr/share/fonts/truetype/D2Coding:ro"
```

## docker-guacd

- official [guacamole/guacd](https://hub.docker.com/r/guacamole/guacd/)
- [D2coding](https://github.com/naver/d2codingfont) font
