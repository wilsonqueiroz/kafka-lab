sudo bin/zookeeper-server-start.sh config/zookeeper.properties

sudo bin/zookeeper-server-start.sh config/zookeeper.properties

sudo bin/kafka-server-start.sh config/server.properties 

sudo bin/kafka-topics.sh --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1 --topic ECOMMERCE

sudo bin/kafka-topics.sh --list --bootstrap-server localhost:9092  

bin/kafka-console-producer.sh --broker-list  localhost:9092 --topic ECOMMERCE

sudo bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic ECOMMERCE --from-beginning


sudo bin/kafka-console-producer.sh --broker-list  localhost:9092 --topic ECOMMERCE  
>PEDIDO0,240
>PEDIDO1,330
>PEDIDO2,56789          
>PEDIDO3,75 
>^C%       