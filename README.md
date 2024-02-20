# Generation
This repository is to explain the different steps required to generate events from MadGraph and then use pythia to generate output files with an hepmc3 extension.

First a generation card is used by MadGraph and an output file ".lhe" is generated.

The output ".lhe" should then be used with the main42.cc example located in the examples directory of pythia.

The syntax to convert from ".lhe" to ".hepmc" is :

./main42 main42.cmnd output.lhe output.hepmc
