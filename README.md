<table>
  <tr>
    <th>License</th><th>Linux</th>
  </tr>
  <tr>
    <td><a href="LICENSE"><img src="https://img.shields.io/badge/license-BSD-blue.svg" title="License"/></a></td>
    <td><a href="https://travis-ci.org/GaloisInc/elf-edit"><img src="https://travis-ci.org/GaloisInc/elf-edit.svg?branch=master" title="Linux"/></a></td>
  </tr>
</table>

# elf-edit
The elf-edit library provides a datatype suitable for reading and writing Elf files.

It is a fork of the original elf package on Hackage, but enables modifying
and serializing Elf files.  These changes are not backwards compatible and hence
we have a new name.

## Building with Stack

To build with Stack, first symlink to one of the provided YAML
files. For example

    ln -fs stack-8.6.yaml stack.yaml
    stack build
