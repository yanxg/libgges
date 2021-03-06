libgges: Grammar-Guided Evolutionary Search
========================================================================

This project was created to support the experimental component of the paper:

P. A. Whigham, G. Dick, J. Maclaurin, and C. A. Owen (2015): "Examining the 'Best of Both Worlds' of Grammatical Evolution" in Proceedings of the 2015 Conference on Genetic and Evolutionary Computation (GECCO 2015), pp. 1111-1118, ACM Press

If you use this project in your work, then a reference to the above
work would be greatly appreciated.

This library was created to give a clean-room implementation of both grammatical evolution (GE) and context-free grammar genetic programming (CFG-GP). Both methods used a common evolutionary strategy, parameterisation method, and so on, to ensure fair comparison between representations.

We have also provided the reference implementations of the problems from our GECCO paper, under the demo directory. Also within the demo directory is a trivial "template" application, from which you can start your own work.

More recently (December 2016), we have included an implementation of Structured Grammatical Evolution (SGE), as presented in the GP & EM paper:

Lourenço, Nuno, Francisco B. Pereira, and Ernesto Costa. "Unveiling the properties of structured grammatical evolution." Genetic Programming and Evolvable Machines: 1-39.

Installation
------------

This project should install on any platform supported by GCC. A
Makefile is included to build the base library and demo application. A
call to:
  make
should compile the project without any problems, and the resulting
binaries should appear in the dist directory.

Documentation
-------------

Documentation for the project can be found in the file [doc.txt](doc.txt)

License
-------

See [LICENSE](LICENSE) file.

Support
-------

Any questions or comments should be directed to Grant Dick
(grant.dick@otago.ac.nz)
