# Exercise SBML databases

In this exercise we will model the phosphorylation of fructose-6-phosphate (F6P), which is the third step of glycolysis, catalyzed by the enzyme [phosphofructokinase](https://en.wikipedia.org/wiki/Glycolysis#Preparatory_phase). F6P is phosporylated to fructose-1,6-bisphosphate (FBP) under the consumption of ATP. 

<img src="https://raw.githubusercontent.com/tbphu/Fachkurs_Bachelor_WS1617/master/sbml_databases/pfk.jpg" alt="pfk" width="400px">

We already have an SBML file which describes this reaction, but without MIRIAM annotations or a kinetic law. 

1. Download the SBML file of the phosphofructokinase reaction [here](https://raw.githubusercontent.com/tbphu/Fachkurs_Bachelor_WS1617/master/sbml_databases/phosphofructokinase.xml) and import the model to Copasi. You will not be able to simulate it yet, because a kinetic law and initial concentrations for the species are missing. Have a look at the species and the reaction of the model.

2. Use Copasi to annotate the species and the reaction of the model. First search for the different species in the [KEGG](http://www.genome.jp/kegg/) compound database and identify their KEGG identifiers. The KEGG compound identifier for water is C00001 for example. For all compounds use the `is` relation. The PFK species is the enzyme catalyzing the reaction and cannot be found in KEGG compount. Instead annotate it with its EC number, which can also be found in KEGG (the resource for EC numbers is ). 

3. Annotate the reaction with the KEGG reaction identifier.

4. We are still missing concentrations for the species in our model. 