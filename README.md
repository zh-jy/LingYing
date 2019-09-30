# LingYing

https://stackoverflow.com/questions/3662995/explaining-apache-zookeeper

Zookeeper is a synchronization service with eventual consistency.

Zookeeper comprises a tree of znodes, which are entities roughly representing file system nodes.

If multiple clients want to get a lock on a resource, they can each concurrently create a sequential znode on a location: whoever gets the loest number is entitled to the lock.

