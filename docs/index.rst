superlance plugins for supervisor
=================================

Superlance is a package of plugin utilities for monitoring and
controlling processes that run under `supervisor
<http://supervisord.org>`_.

Currently, it provides three scripts:

``httpok`` -- This script can be used as a supervisor event listener
(subscribed to TICK events) which will restart a "hung" HTTP server
process, which is defined as a process in the RUNNING state which does
not respond in an appropriate or timely manner to an HTTP GET request.

``crashmail`` -- This script will email a user when a process enters
the EXITED state unexpectedly.

``memmon`` -- See the description below.


Contents:

.. toctree::
   :maxdepth: 2

   memmon

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
