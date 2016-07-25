This is a `pickledb` fork which uses the native `json` module and a few tweaks.


Usage
-----

    >>> import pickledb

    >>> db = pickledb.load('test.db', False)

    >>> db.set('key', 'value')

    >>> db.get('key')
    'value'

    >>> db.dump()
    True
