# protocolsyntax-scriptlets
Various Scripts referenced by protocolsyntax.wordpress.com

Use is permitted, as long as the user understands no support or promise of function implied is provided.

Contents:

linux-chroot: Shell script which takes the path to a linux root in the filesystem as its arguement. The Chroot will be created, necessary filesystems will be mounted, and a shell will be started. Upon exit, the script will attempt to gracefully unmount linux specialty filesystems and return the user to the pervious state. Commonly used to prep a linux jail  prior to starting the Jail on a BSD based system.

