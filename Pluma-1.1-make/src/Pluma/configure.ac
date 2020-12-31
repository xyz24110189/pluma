#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.68])
AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
# 初始话 Automake 
AM_INIT_AUTOMAKE([-Wall]) 
# 这是在 Autoconf 中使用 Libtool 唯一必须的宏
AC_PROG_LIBTOOL
AC_CONFIG_SRCDIR([PluginManager.cpp])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h string.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_HEADER_STDBOOL
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_CHECK_FUNCS([memset strchr])

# 告诉 Autoconf 通过 Makefile.in 自动生成 Makefile 
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
