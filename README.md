# docker-minecraft-bedrock-server
Minecraft Bedrock Edition Server Docker Compose template.

## Run
```
docker-compose up
```
Server will be available at `localhost:19132`

## Restoring Backups
```
docker-compose stop
cd ./survival/worlds/<WORLDNAME>
rm -rf *
unzip ./backups/<WORLDNAME>-<TIMESTAMP>.mcworld
```

## Docs
Read more about Docker images used in the template:
* [Server](https://github.com/itzg/docker-minecraft-bedrock-server)
* [Backup](https://github.com/Kaiede/docker-minecraft-bedrock-backup)
