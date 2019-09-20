# EV-saliva

draw_heat_map - analyze quantified mass data and draw heat maps

This script analyzes quantified mass data of the three saliva samples and draws heat maps.

--------

## Synopsis

draw_heat_map [-a] [-b] [-d] [-e] [-h] [-k] [-l] [-m] [-n] \
              [-o] [-p Accession__of_a_protein] [-r] [-s] [-t] \
              [-v] [-w] [-y sample,protein1,protein2,...]

--------

## Usage

$ perldoc draw_heat_map  
$ draw_heat_map -h  
$ draw_heat_map -a  
$ draw_heat_map -l  
$ draw_heat_map -a -d  
$ draw_heat_map -a -m -d  
$ draw_heat_map -a -b -m -d  
$ draw_heat_map -e -p P60953  
$ draw_heat_map -k -p P27701  
$ draw_heat_map -k -p P27701 -d  
$ draw_heat_map -n -p Q9NQ84  
$ draw_heat_map -n -p Q9NQ84 -d  
$ draw_heat_map -o -p P80748  
$ draw_heat_map -o -p P80748 -d  
$ draw_heat_map -p P05109  
$ draw_heat_map -r  
$ draw_heat_map -r -d  
$ draw_heat_map -s  
$ draw_heat_map -s -d  
$ draw_heat_map -t  
$ draw_heat_map -v  
$ draw_heat_map -w  
$ draw_heat_map -y 4,P01596,P04003,P06737,P63167,Q13347,Q9UL52  

--------

## Options

-h  Print usage  
-a  Draw all the heat maps  
-b  Draw frame lines  
-c  Draw heat colors  
-d  Use the 16 fractions  
-e  Print description of a protein, should be used with -p  
-k  List 0-based peak positions, shold be used with -p  
-l  List of all the proteins  
-m  Enhance heat map colors  
-n  Tabulate ranks, should be used with -p  
-o  Tabulate the area values, should be used with -p  
-p  Draw a heat map of a specified protein  
-r  List of type1 proteins  
-s  List of type2 proteins  
-t  List of type3 proteins  
-v  Print its version number  
-w  Draw stepwise heat colors  
-y  Layer expression levels of specified proteins  
      (samples; 0: 1u, 1: 1l, 2: 2u, 3: 2l, 4: 3u, 5: 3l) 

--------
