# pyro
*A simple python-based tutorial on computational methods for hydrodynamics*


The latest version of pyro is always available at:

https://github.com/zingale/pyro2

The project webpage, where you'll find documentation, plots, notes,
etc. is here:

http://bender.astro.sunysb.edu/hydro_by_example/



## Getting Started

  - make sure you have numpy, f2py, and matplotlib installed on your
    machine
   
     (on a Fedora box, do: yum install numpy numpy-f2py
     python-matplotlib)

  - set the PYTHONPATH environment to point to the pyro2/ directory
    in your .bashrc (or .tcshrc, depending on which shell you use)

  - build the Fortran source.  In pyro2/, type:
  
      ./mk.sh

  - run a quick test of the advection solver:

      ./pyro.py advection smooth inputs.smooth


## Working With Data

  Some problems write a report at the end of the simulation specifying
  the analysis routines that can be used with their data.

  The plot.py script in the pyro2/ directory can be used to directly
  visualize the data from a .pyro output file.


## Getting Help

  Join the mailing list to say up-to-date:

  http://bender.astro.sunysb.edu/mailman/listinfo/pyro-help
