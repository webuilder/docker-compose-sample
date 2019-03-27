# Mysql 5.7 例子

## 命令
启动
```
docker-compose up -d
```

登录数据库
```sh
docker-compose exec mysql mysql -uroot -p
# 或者
docker-compose exec mysql mysql -uuser -p
```

## 数据库参数
参数 | 值
---|---
端口 | 3306
root 用户密码 | root1234
用户名 | user
密码 | user1234
初始化数据库 | testdb
