# Sequence-based-predictor-for-the-impact-of-mutation-on-protein-stabilityby


The objective of this competition is to construct a model that can predict the thermodynamic folding stability of a protein (DDG) in response to a single amino acid mutation. The challenge involves developing a Deep Learning algorithm that is trained on the amino acid sequences of wild-type (WT) proteins and mutant proteins with a single amino acid variation. The ultimate goal of this work is to provide insight into mutation-related diseases and to demonstrate the crucial role played by loss of stability in the loss of protein function. By participating in this competition, you will have the opportunity to contribute to scientific advancements in the field of protein stability, which have significant implications for the diagnosis and treatment of various diseases.

Proteins are large, complex molecules that play many critical roles in the body. They do most of the work in cells and are required for the structure, function, and regulation of the body’s tissues and organs. The overall stability of a protein is influenced by its residues and their interactions. Any change to the wild-type sequence, even a single mutation, has the potential to drastically affect stability because proteins are marginally stable. The effects of non-synonymous variants on the protein stability are quantified in terms of the Gibbs free energy of unfolding (dG). The stability change from a mutated (mutant) protein to its wild-type (wildtype) form is defined as the difference between the folded and unfolded states (dGfolding) and the change in dGfolding when a point mutation is present.

The full description of the Mega-scale dataset can be found: https://www.biorxiv.org/content/10.1101/2022.12.06.519132v1 for background.

#### Extra embedded dataset : https://console.cloud.google.com/storage/browser/indaba-data/train?pageState=
#### Competetion link: https://zindi.africa/competitions/indabax-tunisia-2023

Variable definitions:

ID: Indicated the column index.

pdb_id: It contains the 4 characters ID that represents the PDB structure or otherwise, something like “HHH-rd1-0142” if the structure was generated by Rosetta.

mutation: Mutation applied to the wt_sequence in this pattern; XnY given X is the wildtype amino acid(wt_aa), n is the position number of the amino acid that will be replaced(mutation_pos) and Y is the new amino acid(mut_aa).

wt_seq : WildType sequence. The natural form, appearance or strain existing in the wild protein sequence.

mut_seq: Mutant sequence. A protein sequence that has undergone a change or mutation from the natural form, appearance, or strain existing in the wild protein sequence. This change can involve the addition, deletion, or substitution of one or more amino acids, leading to a modified protein with altered properties and functions.

ddg: Delta Delta G is a metric for predicting how a single point mutation wil affect protein stability.