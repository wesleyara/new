# NEW

New is a simple command line tool that helps you create new files and directories quickly. 

## Installation

To install the tool, you can clone the repository to your home directory.

```bash
# HTTPS
git clone https://github.com/wesleyara/new.git $HOME/new

# SSH
git clone git@github.com:wesleyara/new.git $HOME/new
```

After cloning, add the main script to your bin directory.

```bash
sudo cp $HOME/new/new /usr/bin/new
```

## Usage

To create a new project, you can use the following command:

```bash
# new <project_type> <project_name>
new node my-project
```

The command above will create a new directory called `my-project` with a `package.json` file inside.

## Commands

- `node <project_name>`: Create a new Node.js project.
- `node-ts <project_name>`: Create a new Node.js project with TypeScript.