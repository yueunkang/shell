# Shell Creation

Build my own simple shell capable of changing directories and executing system programs such as `pwd` and `ls`. The goal of this is to familiarize myself with system-related library functions. 

Two main goalsthe
1. Become more familiar with how the OS provides **process control** services that can be invoked by a user application. Specifically, the `shell` will use all three system calls: [fork](https://man7.org/linux/man-pages/man2/fork.2.html), [exec](https://man7.org/linux/man-pages/man3/exec.3.html), and [wait](https://man7.org/linux/man-pages/man2/wait.2.html).    
2. Become familiar with how a program can access a set of system **environment variables** using the [getenv](https://man7.org/linux/man-pages/man3/getenv.3.html) standard library function. 


### Reading
* Process control:
  * [fork](https://man7.org/linux/man-pages/man2/fork.2.html) man page
  * [wait](https://linux.die.net/man/2/waitpid) man page
  * [exec](https://man7.org/linux/man-pages/man3/exec.3.html) man page
  * [Process API](https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf) OSTEP textbook
* Environment variables:
	* [getenv](https://man7.org/linux/man-pages/man3/getenv.3.html) man page
