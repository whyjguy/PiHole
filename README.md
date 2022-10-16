# PiHole


Copy setupVars.conf from setup Pi-Hole instance 

Change host IP in setupVars.conf to match host IP.


##adlists
cant use the adlists.list method as its disable > version 5.0. need to look into gravity.db  methods of changing lists via command line. 



run with ansible-playbook -i inventory --limit DEVELOPMENT playbook.yml --ask-become


