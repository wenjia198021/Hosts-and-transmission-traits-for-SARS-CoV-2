# Hosts-and-transmission-traits-for-SARS-CoV-2

All the datasets and matlab code used for the paper of "In-depth exploraton of hosts and transmission traits for SARS-CoV-2 in COVID-19".

Example: how to determine the classification of SARS-CoV-2 based on the k-mer nature vector, and the corresponding the Neighbour-joining (NJ) phylogenetic tree show the classification of SARS-CoV-2:

Step 1. Put the dataset (hrv.fasta/beta_globin.fasta/influenza_1163.fasta) and matlab under the software of Matlab;

Step 2. Run the code and construct a .meg file named "kmer_natural_vector_for_hrv.meg" for the dataset of "hrv.fasta";

Step 3. Open the .meg file with Mega software (such as MEGA 6.06), and choose the construct/Test Neighbour-Joining Tree ..., you can get a NJ phylogenetic tree for the dataset of hrv.fasta.
