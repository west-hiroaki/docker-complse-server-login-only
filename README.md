# docker-compose-server-login-only

`docker compose` を使って、ubuntu コンテナに bash接続するだけのサンプルです。

## 前提条件

  動作確認は、Mac でのみ行っています。  

## 動作確認手順

  1. コンテナ起動   

      ```bash
      $ docker-complse up -d
      ```

  1. コンテナへの bash 接続   

      ```bash
      $ docker-complse run server /bin/bash
      ```
