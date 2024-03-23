1. Coarse-grained Simulations

To perform the simulations with GENESIS atdyn, please execute the commands as below :
             export OMP_NUM_THREADS=2
             mpirun -np 24 /path_of_GENESIS_installed/bin/atdyn xxxx.inp > xxxx.log

xxxx.inp is the input file of MD and is put in each directory.

2. Analysis

In each simulation directory, there is an "analysis" subdirectory, which includes trajectory analysis scripts. Python3 and plumed packages are required.