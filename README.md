# NAME

Text::Guess::Script - Guess script from text using ISO-15924 codes

<div>
    <a href="https://travis-ci.org/wollmers/Text-Guess-Script"><img src="https://travis-ci.org/wollmers/Text-Guess-Script.png" alt="Text-Guess-Script"></a>
    <a href='https://coveralls.io/r/wollmers/Text-Guess-Script?branch=master'><img src='https://coveralls.io/repos/wollmers/Text-Guess-Script/badge.png?branch=master' alt='Coverage Status' /></a>
    <a href='http://cpants.cpanauthors.org/dist/Text-Guess-Script'><img src='http://cpants.cpanauthors.org/dist/Text-Guess-Script.png' alt='Kwalitee Score' /></a>
    <a href="http://badge.fury.io/pl/Text-Guess-Script"><img src="https://badge.fury.io/pl/Text-Guess-Script.svg" alt="CPAN version" height="18"></a>
</div>

# SYNOPSIS

    use Text::Guess::Script;
    my $guessed_script = Text::Guess::Script->guess($text);

# DESCRIPTION

Text::Guess::Script matches the characters in the text against the script property
and returns the code of script with most characters.

## CONSTRUCTOR

- new()

    Creates a new object which maintains internal storage areas
    for the Text::Guess::Script computation.  Use one of these per concurrent
    Text::Guess::Script->guess() call.

## METHODS

- guess($text)

    Returns the script code with the most characters.

## EXPORT

None by design.

# STABILITY

Until release of version 1.00 the included methods, names of methods and their
interfaces are subject to change.

Beginning with version 1.00 the specification will be stable, i.e. not changed between
major versions.

# SOURCE REPOSITORY

[http://github.com/wollmers/Text-Guess-Script](http://github.com/wollmers/Text-Guess-Script)

# AUTHOR

Helmut Wollmersdorfer <helmut@wollmersdorfer.at>

<div>
    <a href='http://cpants.cpanauthors.org/author/wollmers'><img src='http://cpants.cpanauthors.org/author/wollmers.png' alt='Kwalitee Score' /></a>
</div>

# COPYRIGHT

Copyright 2016-2020 Helmut Wollmersdorfer

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

Locale::Codes::Script
