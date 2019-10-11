Kakebeen et al 2019 Intro
================
Anneke Kakebeen
13 Aug 2019

-   [Repository for analysis of data from Kakebeen et al 2019](#repository-for-analysis-of-data-from-kakebeen-et-al-2019)
-   [Abstract](#abstract)
-   [ATAC](#atac)
-   [SingleCell](#singlecell)
-   [GRN](#grn)
-   [Tail Measurement](#tail-measurement)

Repository for analysis of data from Kakebeen et al 2019
--------------------------------------------------------

This GitLab project holds code for sequencing data preparation, analysis, and figure making for the publication titled Chromatin Accessiblity Dynamics and Sincle Cell Transcriptomics Identify Novel Regulators of Regeneration in Vertebrate Neural Progenitors. This paper can be found with the PMID..... or at this location.

Abstract
--------

Vertebrate appendage regeneration requires precisely coordinated remodeling of the transcriptional landscape to enable the growth and differentiation of new tissue, a process executed over multiple days and across dozens of cell types. This means that heterogeneous and even conflicting gene regulatory decisions must be coordinated in time and space. Given this complexity, it has been difficult to articulate the specific gene regulatory programs enabling regeneration of individual cell types. To better understand how a regenerative program is fulfilled by neural progenitor cells (NPCs) of the injured spinal cord, we analyzed regenerating NPCs isolated from Xenopus tropicalis tails. By intersecting chromatin accessibility data with single-cell transcriptomics, we find that NPCs place an early priority on neuronal differentiation, with an increase in neurons and decrease in the progenitor pool. Late in regeneration, the priority returns to proliferation. Our analyses identify the homeodomain transcription factors Pbx3 and Meis1 as critical regulators of tail regeneration and axon organization. Overall, we articulate transcriptional regulatory dynamics for regenerating NPCs, define discrete windows for NPC cell fate decisions and identify new regulators critical for these decisions.

ATAC
----

This folder contains the commands used to take raw reads to a counts table, quality control analysis, differential accessiblity analysis, and the figures made from this data.

SingleCell
----------

This folder contains the Seurat integrative clustering analysis used to cluster the data, differential expression analysis, and code for figures made from this data.

GRN
---

This folder contains the code used to integrated the ATAC-Seq, scRNA-Seq, and Change et al Bulk RNA-Seq for grn prediction and analaysis.

Tail Measurement
----------------

This folder contains the tail measurement data and graphical representations of this data.