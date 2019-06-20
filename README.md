# cli-in-practice
## split
* `split -a 4 -d -l 1000 filename prefix`
## basename
* `filename=$(basename /path/to/filename)`
## join
* `join file1 file2`
* **file1 and file2 must be sorted on the join fields**
* **left join**: `join -a1 file1 file2`
* **right join**: `join -a2 file1 file2`