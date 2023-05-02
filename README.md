Download Link: https://assignmentchef.com/product/solved-cop3530-programming-assignment-2-hashing-hashing-analysis
<br>
Perform an analysis of hash table number of collisions versus load factor as a function of collision resolution scheme and hash function.

Choose three hash table sizes which differ by at least a multiple of 10 (ex. Size1=100, Size 2=1000, Size 3=10000).

For each hash table size, randomly generate key values between 0 and 3 times the hash table size. As each key value is placed in the hash table, record the current load factor and the number of collisions that have occurred. When counting collisions, for each key there is at most one collision. (Even if the key requires multiple probes to find a spot, this counts as one collision.)

Perform this experiment for any two collision resolution schemes choosing one hash function.

Example Hash function: key mod table size, mid square (square the key, then middle digits modulo table size).

Example Collision resolution schemes: separate chaining, open addressing.

Thus there are 2 experiments with three table sizes per experiment.

Create plots similar to the one below for each experiment. Include number of collisions versus load factor for the three table sizes.

<img decoding="async" src="https://ufl.instructure.com/courses/363464/files/42264130/download">




Your final submission should include:

1. Your implementation of hash tables, collision resolution schemes, and hash function (your source code).

2. Your full report

– Note that the report is 50% of the project grade and should include everything mentioned in the assignment description.

– This assignment has peer reviews which means 80% of the grade will be evaluated by the instructor and 20% by one of your peers.

You can use: <strong>C, C++, Java, Javascript, or Python</strong> for implementation.


