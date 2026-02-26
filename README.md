# weMERFISH
Code for processing whole-embryo MERFISH imaging data written collaboratively by Yinan Wan, Jakob El Kholtei and Bogdan Bintu. 

Corresponding publication: Y. Wan et al ., **Whole-embryo spatial transcriptomics at subcellular resolution from gastrulation to organogenesis** _Science_ 391 , eadt3439 (2026). DOI: 10.1126/science.adt3439

This repo contains the code for 
1) designing primary DNA probes against endogeneous RNAs including sequences homologous to endogeneous RNAs, sequences homologous to linker oligos and primers for PCR amplification and reverse transcription, designing gene-specific linker probes and amplification and read-out probes
  
2) image processing including
  dot detection
  image registration
  cell segmentation
  dot to cell assignment

3) MERFISH decoding of dot indentity

4) cell clustering and cell type analysis

5) integration of single cell multiome data and weMERFISH data
