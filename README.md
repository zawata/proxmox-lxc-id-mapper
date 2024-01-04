# proxmox-lxc-id-mapper
Online LXC id mapper

This tool allows to easily generate a configuration for mapping uid and guid's for an unpriviliged Proxmox LXC.
This is sometimes required to fix permission issues when files/folders are mounted within an LXC.
For more info see: https://pve.proxmox.com/wiki/Unprivileged_LXC_containers

This allows for example to bind UID 1005 both inside of the container to the same UID uotside of the container.

Usage:
containeruid[:containergid][=hostuid[:hostgid]]
Container uid and optional gid to map to host. If a gid is not specified, the uid will be used

To use it simply visit the website : https://kloknibor.github.io/proxmox-lxc-id-mapper/

If it was helpfull please consider :
<script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Support Me on Ko-fi', '#e06f28', 'V7V1SYHL4');kofiwidget2.draw();</script> 
