#文档

### 1.启动服务
- 启动全部服务
```bash
docker-compose up -d
```
- 按需启动部分服务
```bash
docker-compose up -d etcd golang mysql redis
```

### 2.运行代码
将项目代码放置 `CODE_PATH_HOST` 指定的本机目录，进入 `golang` 容器，运行项目代码。
~~~bash
docker exec -it golang bash
~~~