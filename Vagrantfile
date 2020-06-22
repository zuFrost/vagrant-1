# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "generic/centos7"
  config.vm.define "master" do |machine|
  config.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.99.100"
  end
  config.vm.define "node1" do |machine|
  config.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.99.101"
  end
  config.vm.define "node2" do |machine|
  config.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.99.102"
  end
  config.vm.define "node3" do |machine|
  config.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.99.103"
  end
  config.vm.define "node4" do |machine|
  config.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.99.104"
  end
  config.vm.define "nodebd" do |machine|
  config.vm.box_check_update = false
    machine.vm.network "private_network", ip: "192.168.99.105"
  end
end


