# Secure Shell (SSH)

Posted by: Margaret Rouse
WhatIs.com
Follow:
Contributor(s): Michael Cobb

SSH, also known as Secure Socket Shell, is a network protocol that provides administrators with a secure way to access a remote computer. SSH also refers to the suite of utilities that implement the protocol. Secure Shell provides strong authentication and secure encrypted data communications between two computers connecting over an insecure network such as the Internet. SSH is widely used by network administrators for managing systems and applications remotely, allowing them to log in to another computer over a network, execute commands and move files from one computer to another.

SSH can refer both to the cryptographic network protocol and to the suite of utilities that implement that protocol. SSH uses the client-server model, connecting a secure shell client application, the end at which the session is displayed, with an SSH server, the end at which the session runs.

Apart from Microsoft Windows, SSH software is included by default on most operating systems. SSH also supports tunneling, forwarding arbitrary TCP ports and X11 connections while file transfer can be accomplished using the associated secure file transfer or secure copy (SCP) protocols. An SSH server, by default, listens on the standard TCP port 22.

The SSH suite comprises three utilities -- slogin, ssh and scp -- that are secure versions of the earlier insecure UNIX utilities, rlogin, rsh, and rcp. SSH uses public-key cryptography to authenticate the remote computer and allow the remote computer to authenticate the user, if necessary.

The first version of SSH appeared in 1995 and was designed by Tatu Ylönen, a researcher at Helsinki University of Technology who founded SSH Communications Security. Over time various flaws have been found in SSH-1 and it is now obsolete. The current set of Secure Shell protocols is SSH-2 and was adopted as a standard in 2006. It's not compatible with SSH-1 and uses a Diffie-Hellman key exchange and a stronger integrity check that uses message authentication codes to improve security. SSH clients and servers can use a number of encryption methods, the mostly widely used being AES and Blowfish.

As yet, there are no known exploitable vulnerabilities in SSH2, though information leaked by Edward Snowden in 2013 suggests the National Security Agency may be able to decrypt some SSH traffic.

Shellshock, a security hole in the Bash command processor, can be executed over SSH but is a vulnerability in Bash, not in SSH. In reality, the biggest threat to SSH is poor key management. Without the proper centralized creation, rotation and removal of SSH keys, organizations can lose control over who has access to which resources and when, particularly when SSH is used in automated application-to-application processes.
