.. _glossary:

Glossary
========

.. glossary::
   :sorted:

   Pyramid
      A `web framework <http://pylonsproject.org>`_.

   pyramid_mailer
      A `Pyramid add on
      <https://docs.pylonsproject.org/projects/pyramid_mailer/dev/>`_ relied
      upon by ``pyramid_errmail`` to send mail.

   tween
     A bit of code that sits between the Pyramid router's main request
     handling function and the upstream WSGI component that uses Pyramid as
     its 'app'.  The word "tween" is a contraction of "between".  A tween may
     be used by Pyramid framework extensions, to provide, for example,
     Pyramid-specific view timing support, bookkeeping code that examines
     exceptions before they are returned to the upstream WSGI application, or
     a variety of other features.  Tweens behave a bit like WSGI 'middleware'
     but they have the benefit of running in a context in which they have
     access to the Pyramid application registry as well as the Pyramid
     rendering machinery.  See the main Pyramid documentation for more
     information about tweens.
