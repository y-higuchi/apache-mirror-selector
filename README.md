Usage
=====

#### Print preferred mirror URL

    $ ./apache-mirror-selector.py http://www.apache.org/dyn/closer.cgi?path=zookeeper/zookeeper-3.4.6/zookeeper-3.4.6.tar.gz
    http://mirror.olnevhost.net/pub/apache/zookeeper/zookeeper-3.4.6/zookeeper-3.4.6.tar.gz

#### Download from preferred mirror using wget

    $ wget `./apache-mirror-selector.py http://www.apache.org/dyn/closer.cgi?path=zookeeper/zookeeper-3.4.6/zookeeper-3.4.6.tar.gz`

