# Requirements:
* jupyter 5.1.0
* python 3.6.3
* tensorFlow 1.12.0
* sklearn 0.21.3
* pandas 0.20.3
* numpy 1.15.4
* matplotlib 2.2.
* pickle 0.7.4


# Data
The Data file includes 5 subfiles. days_after_mainshock_7 file means the aftershocks that happened within 7 days after the mainshock are seen as postive samples, so as to the other files. Each subfile includes 175 independent earthquakes. Each earthquake is stored in a .csv file. Each row in .csv file is a grid, and also a sample. A sample includes the following columns:
* x: the position of the grid centre relative to the focus of the mainshock
* y: the position of the grid centre relative to the focus of the mainshock
* mainshock_mag: the mainshock magnitude
* aftershock_mag: the aftershock magnitude 	
* sxx: the stress of the xx direction
* syy: the stress of the yy direction	
* szz: the stress of the zz direction	
* syz: the stress of the yz direction	
* sxz: the stress of the xz direction	
* sxy: the stress of the xy direction	
* coulomb: the colomb failure stress	
* maxshear: the maxshear of the stress	
* von: the von-mises stress

# Code
The code file will be run in jupyter.There are totally 7 baseline code files and the DMAP code file.


