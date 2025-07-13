按照如下目录格式创建目录

├── docker-compose.yml
├── keeper
│   ├── config.xml
│   ├── data  <-- 空目录，Docker 会写入数据
│   └── logs  <-- 空目录，Docker 会写入日志
└── clickhouse
    ├── node1
    │   ├── config.xml
    │   ├── users.xml
    │   ├── data  <-- 空目录，Docker 会写入数据
    │   └── logs  <-- 空目录，Docker 会写入日志
    ├── node2
    │   ├── config.xml
    │   ├── users.xml
    │   ├── data
    │   └── logs
    └── node3
        ├── config.xml
        ├── users.xml
        ├── data
        └── logs