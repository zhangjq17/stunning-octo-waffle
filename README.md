
## 【The construction of metagenome-assembled genomes by a combinational strategy of single and co-assembly 】


This directory contains scripts related to the manuscript " TITLE".

### PREPARE

#### Software information

| Software    | Version       | Availability                                                                               |
|-------------|---------------|--------------------------------------------------------------------------------------------|
| bbduk       | 39.01         | https://jgi.doe.gov/data-and-tools/software-tools/bbtools/bb-tools-user-guide/bbmap-guide/ |
| bowtie2     | 2.3.5         | https://github.com/BenLangmead/bowtie2                                                     |
| fastqc      | 0.11.9        | https://www.bioinformatics.babraham.ac.uk/projects/fastqc/                                 |
| kraken2     | 2.1.2         | https://ccb.jhu.edu/software/kraken2/                                                      |
| megahit     | 1.2.9         | https://github.com/voutcn/megahit                                                          |
| spades.py   | 3.13.0        | https://github.com/ablab/spades                                                            |
| quast.py    | 5.2.0         | https://github.com/ablab/quast                                                             |
| metawrap    | 1.3.2         | https://github.com/bxlab/metaWRAP                                                          |
| gtdbtk      | 2.1.1         | https://github.com/Ecogenomics/GTDBTk                                                      |
| prodigal    | 2.6.3         | https://github.com/hyattpd/Prodigal                                                        |
| tRNAscan-SE | 2.0.12        | https://github.com/UCSC-LoweLab/tRNAscan-SE                                                |
| rnammer     | 1.2           | https://services.healthtech.dtu.dk/services/RNAmmer-1.2/                                   |
| cmscan      | 1.1.4         | http://eddylab.org/infernal/                                                               |
| antismash   | 6.1.1         | https://github.com/antismash/antismash                                                     |
| diamond     | 2.0.14.152    | https://github.com/bbuchfink/diamond                                                       |
| pfam_scan   | 1.6           | http://ftp.ebi.ac.uk/pub/databases/Pfam/Tools/                                             |
| RGI         | 6.0.2         | https://github.com/arpcard/rgi                                                             |

#### Database information

|        Database       |                    Version/Time stamp                    | Availability/Database website                                                         |
|:---------------------:|:--------------------------------------------------------:|---------------------------------------------------------------------------------------|
|          CARD         | prevalence-v4.0.0,   broadstreet-v3.2.5, ontology-v3.2.5 |                               https://card.mcmaster.ca/                               |
| card.json   (RGI_use) | 2023/1/28                                                |                          https://card.mcmaster.ca/latest/data                         |
|          VFDB         | 2022/11/11                                               |                               http://www.mgc.ac.cn/VFs/                               |
|          COG          |  2022/3                                                  |                       https://www.ncbi.nlm.nih.gov/research/cog/                      |
|          CAZy         | CAZyDB.08062022                                          |                                  http://www.cazy.org/                                 |
|          KEGG         | KEGG FTP   Release 2022-11-07                            |                              https://www.genome.jp/kegg/                              |
|          Pfam         | 2021/11/15                                               |                              http://pfam-legacy.xfam.org/                             |
|        BacMet2        | version 2.0                                              | http://bacmet.biomedicine.gu.se/download_temporary.html                               |
|       SwissProt       | SwissProt   2022/10/12                                   | https://ftp.uniprot.org/pub/databases/uniprot/current_release/knowledgebase/complete/ |
|       UniRef100       | Release:   2022_04, 12-Oct-2022                          |    https://ftp.uniprot.org/pub/databases/uniprot/current_release/uniref/uniref100/    |
|        MetaCyc        | MetaCyc 25.1                                             |                                  https://metacyc.org/                                 |
|          Rfam         | Release 14.9                                             |                                   https://rfam.org/                                   |


### INSTRUCTION OF PIPELINE

There are four part of metagenomic analysis, including single sample assembly part, co-assembly part, the combination of single sample assembly's and co-assembly's result and the annotation for genomes.

#### Single sample assembly part

##### The construction of metagenome-assembled genomes single sample assembly

###### QC.sh

###### Run_assembly.sh

###### Run_binning.sh

####  Co-assembly part

###### Run_kraken.sh

#### The combination of single sample assembly's and co-assembly's genome




#### The annotation for genomes

Same steps for both single sample assembly genomes and co-assembly genomes.


##### Run_annotation.sh




