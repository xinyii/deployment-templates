# MySQL

## 步骤

### 配置防火墙（host 网络模式）

```shell
firewall-cmd --zone=public --add-port=3306/tcp --permanent
firewall-cmd --reload
```

### MySQL Admin

```shell
docker run -d --name mysql-adminer \
  -p 8080:8080 \
  adminer
```

## 参考

- <https://www.cnblogs.com/xiaocheng12138/articles/16299367.html>
