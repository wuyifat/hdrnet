system preperation:
ubuntu 16.04
Ubuntu 18.04 TLS has moved to CUDA 9.1 now, which deprecates the Nvidia Fermi Architecture. So use Ubuntu 16.04 will be straightford.

cuda 8.0
cudnn v5.1 for cuda8.0
newer cudnn versions creates conflicts.
some latest cudnn versions only provides .deb and no .run files. .deb file doesn't install correctly on ubuntu. Need to use the .run file.
follow scrapbook51.wordpress.com to install

errors and fixes during build
