# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provider :virtualbox do |vb|
    vb.customize [ 'modifyvm', :id, '--name', 'valdes-00' ]
    vb.customize [ 'modifyvm', :id, '--cpus', '4' ]
    vb.customize [ 'modifyvm', :id, '--memory', '512' ]
    vb.customize [ 'modifyvm', :id, '--cpuexecutioncap', '50' ]
  end
end