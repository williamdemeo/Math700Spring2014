Math 700: Linear Algebra, Spring 2014
=====================================

**Instructor:** William DeMeo  
**Email:** williamdemeo@gmail.com  
**Office:** LeConte College, Room 314C  
**Office hours:** Wed 11-12; Fri 11-12 & 1-2; and by appointment.  
**Class meeting times:** MW, 3:55--5:10, LeConte, Room 310.  
**Webpage:** http://williamdemeo.github.io/LinearAlgebra

-----------------------------------------------------------------------
- [Overview](#overview)
- [Textbook](#textbook)
- [Homework](#homework)
- [Exams](#exams)
- [Course topics](#course-topics)
- [Computing](#computing)
	- [Sage](#sage)
	- [Git and GitHub](#git-and-github)
	- [Submitting Homework](#submitting-homework)


Overview
--------
This course in linear algebra is aimed at beginning graduate students in
mathematics.  It may also be appropriate for advanced undergraduate math majors,
and graduate students in engineering and computer science.  The focus is on
finite dimensional vector spaces from a more general point of view than one
finds in an undergraduate course.  Some of the topics covered are the following
(from the catalog): vector spaces, linear transformations, dual spaces,
decompositions of spaces, canonical forms.  A more detailed list of topics
appears below. 

Textbook
--------
[The Linear Algebra a Beginning Graduate Student Ought to Know](http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.9789400726352&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FLinear-Algebra-a-Beginning-Graduate-Student-Ought-to-Know%2FJonathan-S-Golan%2Fe%2F9789400726352), Jonathan Golan.
<!-- GOLAN -->
<a href="http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.9789400726352&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FLinear-Algebra-a-Beginning-Graduate-Student-Ought-to-Know%2FJonathan-S-Golan%2Fe%2F9789400726352">
<IMG border=0 src="http://images.barnesandnoble.com/images/229900000/229902005.JPG" ></a><IMG border=0 style="width: 50px;" src="http://ad.linksynergy.com/fs-bin/show?id=xEro7OMQWE4&bids=239662.9789400726352&type=2&subid=0" >

**Other references:**
[Linear Algebra and Its Applications](http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.9780471751564&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FLinear-Algebra-and-Its-Applications%2FPeter-D-Lax%2Fe%2F9780471751564), Peter Lax.  
[Finite Dimensional Vector Spaces](http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.9781614272816&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FFinite-Dimensional-Vector-Spaces%2FPR-Halmos%2Fe%2F9781614272816), Paul Halmos.  
[Matrix Analysis](http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.2580521386329&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FMatrix-Analysis%2FRoger-A-Horn%2Fe%2F2580521386329), Horn and Johnson.   
[Matrix Computations](http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.9780801854149&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FMatrix-Computations%2FGene-H-Golub%2Fe%2F9780801854149), Golub and Van Loan.  
[Advanced Linear Algebra](http://click.linksynergy.com/link?id=xEro7OMQWE4&offerid=239662.9780387728285&type=2&murl=http%3A%2F%2Fsearch.barnesandnoble.com%2FAdvanced-Linear-Algebra%2FSteven-Roman%2Fe%2F9780387728285), Steven Roman.

Homework
--------
Solving problems is the best way to learn this material.  A list of problems,
both from the textbook and other sources, will be distributed and updated as the
course progresses.  Students will solve and submit as many solutions as
possible.  In addition, for each homework assignment, two students will be
responsible for typing up correct soltuions to the homework problems using LaTeX
and submitting them to the class GitHub repository. 
(See [Git and GitHub](#git-and-github) below.)  Homework is worth 50% of the
course grade.


Exams
-----
There will be one midterm exam worth 20% of the course grade.
It will be scheduled as we progress, and notice of at least one week will be
given prior to the date of a test.  A final exam at the end of the semester will
be worth 30% of the course grade.


Course topics
-------------
1.  Fields; vector spaces; algebras over a field; isomorphism theorems.
5.  Linear independence; basis and dimension.
6.  Linear transformations.
7.  The endomorphism algebra of a vector space.
8.  Representation of linear transformations by matrices.
8.  Lattice of subspaces and invariant subspaces.
9.  Systems of linear equations.
9.  Determinant and trace.
9.  General and special linear groups: orthogonal and unitary groups.
9.  Spectral theory: eigenvalues, eigenvectors.
9.  Euclidean structure: orthonormal basis, norms, spectral radius.
9.  Normed linear spaces and duality.
9.  Spectral theory of self-adjoint mappings.

**Other topics (depending on time and student interest)**

+  Krylov subspaces.
+  Self-adjoint endomorphisms.
+  Unitary and normal endomorphisms.
+  Moore-Penrose pseudoinverses.
+  Bilinear transformations and forms.
+  Matrix inequalities and decompositions.
+  Algebras of linear transformations, simultaneous triangularization.

-----------------------------------------------------------------------------
Computing
=========
No prior programming experience is required for this course, and the computing
component of the course will be fairly minimal.  However, all students must know
(or learn) how to type up solutions to *some* of the homework problems using 
[LaTeX][], and all students must know (or learn) how to submit *some* of these
solutions using [Git][] and [GitHub][].  (More information about this below.)

Sage
----
This is a graduate math course, so it will be taught from a more abstract and
general perspective than undergraduate linear algebra.  However, one of the best
ways to develop a deeper understanding of this subject is to use the computer to
experiment with and apply the theory.  For this we will use the open source math
software called [Sage][].  Sage essentially provides a [Python][] interface to
a [vast array][] of well developed and powerful open source mathematical software.

Getting started with Sage is extremely easy.  You don't even need to install any
software. By using Sage though a web browser you can and do all your computing
and store all your sage "worksheets" in the cloud.

It's also possible to download and install Sage on your own computer.  It is free
and is not hard to install. 

If you've used Sage before and just need a quick refresher, 
check out the [Sage Quick Start Guides](http://www.sagemath.org/doc/prep/quickstart.html).  
Be sure to check out the Sage linear algebra documentation:

+ [Sage Quick Start Section: Linear Algebra](http://www.sagemath.org/doc/prep/Quickstarts/Linear-Algebra.html)
+ [Sage Guided Tour Section: Linear Algebra](http://www.sagemath.org/doc/tutorial/tour_linalg.html)

If you are brand new to Sage, please try the following:

1. Go to http://www.sagemath.org/ and click [Try Sage Online](http://cloud.sagemath.com/).  
2. [Getting stated using Sage](http://www.sagemath.org/doc/prep/Logging-On.html) explains how to create an account.  
3. Check out the [Sage Thematic Tutorials](http://www.sagemath.org/doc/thematic_tutorials/index.html)


Git and GitHub
--------------
In this class, occassionally you will have to submit a homework assigment using 
[Git][] and [GitHub][].  These are powerful software services that make it easy
to maintain and collaborate on projects.  You are not expected to have heard of
Git or GitHub before this class, and I am more than willing to work with any
student who has limited experience with or knowledge of computers or computing.

If you are new to Git, please try the [15 Git minute tutorial][].  Also, the
[git--the simple guide][] and the [GitHub help pages][] are excellent.

Git is very easy to use, and you only need the very basics for what we will do
in this class.  But [the main reason Git was created][] (by Linus Torvalds) was
to make it very easy to do more sophisticated things like branching and 
merging that improve workflow and ease collaboration.

Submitting Homework
-------------------
All students should try to solve all of the assigned homework problems.
However, not all solutions will be collected and graded.  Instead, for each
assignment, on a rotating basis, two students will be responsible for solving
and writing up "official" solutions for the given assignment. These students
will then submit their solutions to the [Math700Homework][] repository. Other students
will then have a chance to look at the official solutions and check them against
their own work.  At any time thereafter, any student may submit corrections or
suggestions for improving the official solutions. 

For each assignment, the two designated problem solvers should submit their 
joint work as follows:

1. Solve the problems. (Try to make sure they are correct. Consult each other
   and the prof if necessary.)   
2. Type up your solutions using [LaTeX][] and save in a single file, e.g.,
   Homework01.tex.   
3. [Set up Git][] on your computer.   
4. [Fork][] the [Math700Homework][] repository to your computer. (to be demonstrated in class)   
5. Copy your solution file into the directory Math700Homework/Solutions on your computer.   
6. [Commit][] your changes.   
7. Submit a [pull request][]. (to be demonstrated in class)  

**Resources:**
+ [Learn Git in 15 minutes][]  
+ [git--the simple guide][]  
+ [Git Help][]  
+ [LaTeX Guide][]  
+ [A Beginner's Guide to LaTeX][]  


Online Discussion Forum
-----------------------
If we find it useful to have an extensive online dialog, 
we might consider other tools as the semester progresses.  
For now, however, anyone in the class can start a dialog
with the rest of the class by creating a [New Issue][] in 
this respository, or in the [Math700Homework][] repository. 

[New Issue]: https://github.com/williamdemeo/LinearAlgebra/issues
[LaTeX]: http://en.wikipedia.org/wiki/LaTeX
[GitHub]: http://en.wikipedia.org/wiki/Github
[Git]: http://en.wikipedia.org/wiki/Git_(software)
[Sage]: http://en.wikipedia.org/wiki/Sage_(mathematics_software)
[vast array]: http://en.wikipedia.org/wiki/Sage_(mathematics_software)#Software_packages_contained_in_Sage
[Fork]: https://help.github.com/articles/fork-a-repo
[pull request]: https://help.github.com/articles/using-pull-requests
[Set up Git]: https://help.github.com/articles/set-up-git
[Commit]: http://rogerdudler.github.io/git-guide/
[Git Help]: https://help.github.com/articles
[The basics of Git in 15 minutes]: http://try.github.io/levels/1/challenges/1
[Learn Git in 15 minutes]: http://try.github.io/levels/1/challenges/1
[15 minute tutorial]: http://try.github.io/levels/1/challenges/1
[A Beginner's Guide to LaTeX]: http://www.cs.princeton.edu/courses/archive/spr10/cos433/Latex/latex-guide.pdf
[LaTeX Guide]: http://en.wikibooks.org/wiki/LaTeX
[Git--the simple guide]: http://rogerdudler.github.io/git-guide/
[GitHub help pages]: https://help.github.com/
[the main reason Git was created]: http://youtu.be/4XpnKHJAok8
[Math700Homework]: https://github.com/williamdemeo/Math700Homework
[15 Git minute tutorial]: http://try.github.io/levels/1/challenges/1