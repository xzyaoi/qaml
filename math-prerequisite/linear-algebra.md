# Linear Algebra

In this chapter, we will discuss some basic math in Linear Algebra, that would probably include matrix, vectors etc.

## Scalar, vector, matrix, and tensor.

A _vector_ is an ordered finite list of numbers. Vectors are usually written as vertical arrays, surrounded by square or curved brackets, as seen below.

$$\begin{pmatrix}-1.1 \\\ 0.0 \\\ 3.6 \\\ -7.2 \end{pmatrix} or \begin{bmatrix}-1.1 \\\ 0.0 \\\ 3.6 \\\ -7.2 \end{bmatrix}$$

Sometimes, they are written as numbers separated by commas and surrounded by parentheses. As seen below.

$$(-1.1, 0.0, 3.6, -7.2)$$

Vector is often denoted by a lowercase symbol $$a$$ . We can get the element \(also known as entries, coefficients or components\) of a vector by the index, and the $$i_{th}$$ element of the vector a is therefore denoted as $$a_i$$ where the subscript $$i$$ is an integer index of the vector.

If two vectors have the same size, and more importantly, each of the corresponding entries is the same, then the two vectors are equal, which is denoted as $$a = b$$ 

A _scalar_ is a number or a value. In most applications, scalars are real numbers. We usually use an italic lowercase symbol to denote a scalar. For example, $$\textit{a}$$ is a scalar.

A _matrix_ is a rectangular array, which means it is a 2-dimensional data table at the same time. Matrix is a collection of items that have the same feature and character. In a matrix, a column indicates a feature, and a row indicates an item. Matrix is usually denoted as a capital letter, $$A$$ for example.

A _tensor_ is an array with more than 2 dimensions. Generally, if the elements of an array are distributed in a regular grid with several dimensions, we would call it a _tensor_. We use a capital letter to denote a tensor, same with the matrix.$$A$$for example. An element in a tensor is denoted as $$A_(i,j,k...)$$ .

**Relations between them**

_Scalar_ is a 0-dimensional tensor. _Vector_ is a 1-dimensional tensor. For example, with a scalar, we could get the length of a rod, but we cannot know the direction of this rod.

With a vector, we could know both the length and direction of a rod.

With a tensor, we may be able to know both the length and direction of a rod, and we could even know more about the rod. \(for example, the degree of deflection\)

#### Relations between tensor and matrix.

From the aspect of algebra, the matrix is a generation of the vector, the matrix is a 2-dimensional table. $$n$$-dimensional is a so-called $$n$$-dimensional table. Noted that this is not a strict definition of the tensor.

For the aspect of geometry, a matrix is a geometric sense value. It does not change with the coordinate transformation of the frame of reference. the vector has this feature too.

The tensor can be represented by a $$3 * 3$$ matrix or an $$n * n$$ matrix.

A scalar can be regarded as a $$1 * 1$$ matrix while a vector with $$n$$ items can be regarded as $$1 * n$$ matrix.

#### What will happen if I multiply a matrix and a tensor?

_A_. You can only multiply an $$m * n$$ matrix and a $$n$$ items vector. Then you will get an $$m$$ items vector. The key to this is regarded each row of the matrix as a vector, and multiply the given vector.

For example, If you are going to multiply the following:

$$\begin{bmatrix}1, 2 \\\ 0.0, 1 \\\ 3.6, 3 \\\ -7.2,2 \end{bmatrix}$$ and $$\begin{bmatrix}-1.1 \\\ 0.0 \\\ 3.6 \\\ -7.2 \end{bmatrix}$$

## Norm.

Norm is a measure of its magnitude or length. We say a vector is large if its norm is a large number, and we say it is small if its norm is a small number.

In mathematics, a norm is _**a function that assigns a strictly positive length or size to each vector in a vector space**_. There are many different types of norms for a vector or a matrix. For example,

_L1-norm_: $$L_1$$ norm is also called the taxicab norm or the Manhattan norm. This is because it uses Manhattan distance as the length. It is also known as one-norm, mean norm or $$\ell_1$$ norm.

$$L_1(v) = ||v||_1$$ , and

$$L_1(v) = |a_1| + |a_2| + ... + |a_n|$$ 

For example, the $$L_1$$ norm of vector  $$(1,2,3)$$  is:

$$L_1(v) = 1 + 2 + 3 = 6$$ 

\_\_$$L_2$$_-norm_: $$L_2$$-norm is also called Euclidean norm since it uses euclidean distance. It is also known as **mean-square norm**, least-squares norm or $$\ell_2$$-norm.

$$L_2(v) = ||v||_2$$ , and

$$L_2(v) = \sqrt{a_1^2 + a_2^2 + ... + a_n^2}$$

For example, the $$L_2$$ norm of vector$$(1,2,3)$$is:

$$L_2(v) = \sqrt{1^2 + 2^2 + 3^2}  =  3.74..$$\_\_

_Max-norm_. Max-norm is defined as the maximum of the absolute values of its components. It is also known as$$L\infty$$_-norm,_  $$\ell\infty$$-norm, infinity norm or uniform norm.

For example, the max norm of vector $$(1,2,3)$$$ is:

$$ ||(1,2,3)||_\infty =max(|1|,|2|,|3|) = 3$$

#### Properties of $$L_2$$ Norm

* Non-negative homogeneity.
* Triangle inequality.
* Non-negativity.
* Definiteness.

####  positive definite matrix?

#### 

#### eigenvalue? eigenvector? eigenvalue decomposition?

#### singular value? singular value decomposition?

#### differences between singular value and eigenvalue? and what about their decomposition?

