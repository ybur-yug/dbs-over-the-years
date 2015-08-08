# Databases. They Save Things.

## What?
This is a look at databases. From then, til now. It is also a WIP.

### The Beginning

#### *The Human Era*

In this time, we stored things ourselves. Refernces and referents are common. We come up with
elaborate systems to store nontrivial amounts of 'things' and 'stuff' out of necessity. This
task, which would be torture for even the most anal retentive of humans, churns on for decades until
some jerk named 'Turing' comes and says we might be able to 'computer' and 'computers' can 'store'
data. Riiiiiiiight.

#### The 60's: No Summer of Database Love

The data models:

**CODASYL**
Conference on Data System Languages. These guys got together in '59, and they eventually lead to the
development of COBOL.

They were really the first to (attempt) at standardizing data base interfaces. Not much else they did
affected much but this was sort of a big deal.

They were the first (and probably) only group to ever form a **`List Processing Task Force`**

10 years after they start, they release the first language specifications for the `network database model`,
which later became known as the Codasyl Data Model.

It had a few specific languages:

A `data definition language` (DDL) to define schema, another for subschemas and defining application views
of the database, and a `data manipulation language` (DML) defining verbs for embedding COBOL to request
and update data from the server.

Now, you might think "This is old as shit. Why would I never need to know about it?"

### *Well*, \*ahem\*

#### [You can still run this shit](http://www.oracle.com/technetwork/products/rdb/index-086844.html)

Thanks, Oracle.

And here's their note on it:

```markdown
 CODASYL DBMS is a multiuser, CODASYL-compliant database management system for OpenVMS operating systems. CODASYL DBMS is designed for databases of all levels of complexity, ranging from simple hierarchies to sophisticated networks with multilevel relationships. CODASYL DBMS proivides a reliable operating platform for application environments where stability, high availability, and throughput are essential.

 CODASYL DBMS provides options supporting very large memory addressing and hot standby for performance and availability. Release 7 also offers added improvements for reliability to manufacturing and shop floor control environments using this database.

 Very Large Memory Addressing Support: A shared record cache allows the DBMS to use as much physical memory as a computer system can support, so that frequently accessed records can be stored in memory and reduce disk I/O. The advantages include reduced overhead and improved response time.

 Hot Standby: The Hot Standby prevents the DBMS database from becoming a single point of failure by physically duplicating the database at a geographically remote site. In the event of failure, the "hot standby" database becomes the master database and takes over application processing. This does not require specific hardware to operate, and no changes to the application code are needed.

```

**IMS**

## 70s

## 80s

## 90s

## 00's and On

# Principles

## ACID

## BASE

## CAP

## Paxos

## Raft

## NoSql

