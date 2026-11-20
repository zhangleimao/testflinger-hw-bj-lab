# testflinger-hw-bj-lab 

Testflinger-agent-charm-configs
This repository stores the agent configs for Testflinger agents hosted in Huawei Beijing Lab (data-hw-bj)

data-hw-bj: This folder contains the agents configs for machines in data-hw-bj 

Update Testflinger agent configs
  $ ssh x157 # vpn required 
  $ juju run <agent-host-charm-unit> update-configs  

Prerequisites
 Deploy latest version of Testflinger agent hosts according. 
  https://ubuntu.com/docs/testflinger/latest/how-to/administer-agent-hosts/  
