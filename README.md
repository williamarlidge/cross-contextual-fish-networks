## Cross-contextual differences in social networks of small-scale fisheries and the implications for bycatch information-sharing

The following repository contains all the R script for the following unpublished manuscript:

'Arlidge WNS, Firth JA, Alfaro-Shigueto J, Ibañez-Erquiaga B, Mangel JC, Squires D, Milner-Gulland EJ. (2020). 
Understanding the potential for information spread about fisheries bycatch reduction initiatives using cross-contextual 
information-sharing networks'

The files are complete and correct as of XX XXX 2020. Please direct any queries or corrections to 'william.arlidge@gmail.com'


## 1. System requirements

R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and MacOS. 

This R-script has been run on R version 3.6.0.

To run this custom R-script, please download the script files to your computing system and load the scripts into the R working environment (see Instructions for Use). 


## 2. Installation guide

You can download R, here: https://www.r-project.org/

If you have questions about R, like how to download and install the software, or what the license terms are, please read the the r-project's answers to frequently asked questions (https://cran.r-project.org/faqs.html). 

Once your have downloaded your preferred CRAN mirror, the install time should take about a minute. 


## 3. Demo

The full dataset underpinning the cross-contextual differences in social networks of small-scale fisheries and the implications for bycatch information-sharing manuscript is availale for use. The available code runs the complete analysis. We have not provided a demo for use, but please contact william.arlidge@gmail.com if you have any specific querries regarding a demo for use.


## 4. Instructions for use

The following repository contains the following 12 files:

 i. 'Plot_Fig2.R' The R-script to recreate panels B-D for figure 2 showing the structure of information-sharing in relation to turtle bycatch. Note that panel A of Figure 2 was generated in ArcGIS and integrated using Abobe Illustrator. 
 
 ii. 'Plot_Fig3.R' The R-script to recreate figure 3 showing the observed correlation (and the correlations expected under the null models)between the turtle bycatch information-sharing network with all the other information networks.
 
 iii. 'Plot_Fig4.R' The R-script to recreate Supplementary Information figure S1 showing illustrative networks of the structure of information sharing across contexts. 
 
 iv. 'Plot_Fig5.R' The R-script to recreate Supplementary Information figure S2 showing the observed assortativity coefficient for outgoing links in comparison to the null distributions for the different information-sharing networks.
 
 v. 'Plot_Fig6.R' The R-script to recreate Supplementary Information figure S3 showing the observed variance in node betweenness in comparison to the null distributions for the different information-sharing networks.
 
 vi. 'Plot_Fig7.R' The R-script to recreate Supplementary Information figure S4 showing the observed mean node eccentricity in comparison to the null distributions for the different information-sharing networks.
 
 vii. 'Plot_Fig8.R' The R-script to recreate Supplementary Information figure S5 showing the observed variance in node eccentricity in comparison to the null distributions (generated from the context permutations) for the different information-sharing networks.
 
 viii. 'Plot_Fig8.R' The R-script to recreate Supplementary Information figure S6 showing the observed mean node eccentricity in comparison to the null distributions (generated from the context permutations) for the different information-sharing networks.

ix. 'Plot_Fig9.R' The R-script to recreate Supplementary Information figure S7 showing context differences to the ‘any’ nomination network.

x. 'Plot_Fig10.R' The R-script to recreate Supplementary Information figure S8 showing output for evaluation of context null model 2.

xi. 'Plot_Fig11.R' The R-script to recreate Supplementary Information figure S9 showing observed correlation (and the correlation expected from the context permutations) between all of the information-sharing networks.

xii. 'Plot_Fig12.R' The R-script to recreate Supplementary Information figure S10 showing observed correlation (and the correlation expected from the edge permutations) between all of the information-sharing networks.

Load each file in R using the command:
df <-read.csv("add_your_computers_file_path_here")
