# Makefile for priority/basic plugin

AUTOMAKE_OPTIONS = foreign

PLUGIN_FLAGS = -module -avoid-version --export-dynamic

INCLUDES = -I$(top_srcdir) -I$(top_srcdir)/src/common

pkglib_LTLIBRARIES = priority_basic.la

# basic priority logging plugin.
priority_basic_la_SOURCES = priority_basic.c
priority_basic_la_LDFLAGS = $(SO_LDFLAGS) $(PLUGIN_FLAGS)
