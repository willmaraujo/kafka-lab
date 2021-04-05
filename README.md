# start zookeeper service
zookeeper-server-start config/zookeeper.properties

# start kafka
kafka-server-start config/server.propertiers

# consumer
kafka-console-consumer --bootstrap-server 127.0.0.1:9092 --topic first_topic --group my-third-app

