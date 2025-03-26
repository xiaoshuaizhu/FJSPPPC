# FJSPPPC
-in the first line there are (at least) 2 numbers: the first is the number of jobs and the second the number of machines
-Every row represents one job: the first number is the number of operations of that job, the second number (let's say k>=1) is the number of machines that can process the first operation; then according to k, there are k pairs of numbers (machine, processing time, processing power) that specify which are the machines, the processing times and the processing power; then the data for the second operation and so on...

Example: 0test
3 4
3  3  1 10  9  2  9 10  4  5  4  3  1  3 10  2  7  8  3  6  4  3  1 10  5  3  9  7  4  6 10
3  3  2  7 10  3  7  5  4  1 10  3  1 13 10  3  5  7  4 10  9  3  1  5  4  2  2  6  3  8 10
3  2  2  7  9  3  4 10  3  1  4  8  3  7  4  4  2  9  3  2  4 10  3  3  8  4  6  9

first row = 3 jobs and 4 machines 
second row: job 1 has 3 operations, the first operation can be processed by 3 machine that is machine 1 with processing time 10 and processing power 9, machine 2 with processing time 9 and processing power 10, and machine 4 with processing time 5 and processing power 4.
