# Docker image for chrome-stable w/ x11vnc

```
docker run -d --name chrome yokogawa/chrome-vnc
docker inspect --format='{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' chrome
172.17.0.2
```

172.17.0.2:5900 に接続する

