
# Project Terminator — Lab Journal

## November 15–21, 2026 — Initial Setup and Configuration

### 1. Windows 11 Installation and Dual-Boot Setup

I started Project Terminator on November 15, 2026, by reinstalling Windows 11 on my laptop.

After installing Windows 11, I decided to install a second operating system, Ubuntu Linux, to create a dual-boot environment.

### 2. Disk Partitioning and Storage Management

I divided my SSD into several partitions and volumes:

- **C: WINDOWS — 300 GB:** Windows 11, applications, and user files.
- **D: SHARED — 100 GB:** Storage for sharing files between Windows and Ubuntu.
- **E: IT-LABS — 25 GB:** Storage for IT practice and experiments.
- **Ubuntu — approximately 50 GB:** Space allocated for Linux.

I also practiced disk and volume management using DiskPart, including creating and managing virtual disks (VHD/VHDX).

### 3. Windows User Management and Security

I practiced managing local Windows user accounts and groups.

I also configured NTFS permissions to control access to files and folders.

### 4. Debian 13 Server Installation

I installed Debian 13 on a separate desktop computer to use as the company server in Project Terminator.

## November 22, 2026 — Initial Setup and Configuration


### 5. Linux Network Configuration

Initially, the Debian server did not have an IPv4 address on its Ethernet interface.

I investigated the network configuration and configured the Ethernet interface `enp4s2` to use DHCP.

The Debian server successfully obtained the IP address `192.168.0.160`.

### 6. SSH Remote Administration

I installed OpenSSH Server on Debian 13.

I established an SSH connection from my Windows 11 laptop to the Debian server.

During the initial connection, I verified the server's ED25519 SSH host key fingerprint.

After authentication, I successfully executed Linux commands remotely through Windows PowerShell.


