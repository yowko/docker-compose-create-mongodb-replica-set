# docker-compose-create-mongodb-replica-set

1. add hosts

  ```bash
  sudo echo "127.0.0.1 mongo1\n127.0.0.1 mongo2\n127.0.0.1 mongo3" >> /etc/hosts
  ```

2. create mongodb replica set

  ```bash
  docker-compose up -d
  ```
