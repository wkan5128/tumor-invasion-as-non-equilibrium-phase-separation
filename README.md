# tumor-invasion-as-non-equilibrium-phase-separation
This repository contains processed data and code to reproduce key figures in the manuscript titled above. 

- Macrospheroid data from two cell lines MCF-10A and MDA-MB-231 (shape and dynamics data) at 2mg/ml and 4mg/ml conditions are stored in their respective folders. Data structure is as follows 
shapdis. mat - x,y,z,cell shape metric
frameXX.mat - x,y,x velocity component, y velocity component, frame number
- Microspheroid data are also stored in folder titled microspheroid folder for early and late stage microspheroids (data structure in rottracks witht times
- Analysis.m will process the data stored to produce the trends in the paper
- Countnuclei.m is the main script that will call sub-functions for cell counting algorithm used to preprocess multiphoton microscopy images to identify nuclei location and cell counts
