This repository used in the study: 
Crustal heterogeneity controls the along-strike segmentation: Analog and numerical models of the northern South China Sea
Gengxiong Yang, Hongwei Yin*, Christian Schiffer, Sascha Brune, Dong Jia, Wei Wang 


The folder primarily contains the output results (which can be directly visualized using ParaView) of two experiments controlled by two influencing factors 
and the corresponding parameter files.

The parameter files are named MAZ.prm and FBZ.prm:

MAZ: Magma Arc Zone
FBZ: Forearc Basin Zone

In MAZ.prm, the use of Diabase represents the Magma Arc, 
simulating the extensional process of the northern South China Sea margin under the influence of a magmatic arc.

In FBZ.prm, the pre-existing sedimentary layers increase the thickness of the brittle layer while maintaining a thinner ductile layer, 
simulating the extensional process of the northern South China Sea margin influenced by the Forearc Basin.

The output folder includes not only data for visualization (solution.pvd) but also the following files:
1.Log file (log.txt)
2.Detailed explanations of all relevant parameters (parameters.prm)
3. Statistics for time steps, velocity, temperature, and heat flow (statistics_file)

Model runs in the study used dealii 9.3.3.
The ASPECT version is 2.4.0-pre (main, 6496f3176)

ASPECT version used for this study is found at: 
https://github.com/geodynamics/aspect






