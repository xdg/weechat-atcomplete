# NAME

atcomplete.pl - complete nicks when prefixed with '@'

# DESCRIPTION

This plugin for the [weechat](http://weechat.org/) IRC client allows
completing nicks when prefixed with '@'.  This allows highlighting users in
IRC gateways for Slack, Flowdock, etc. that require '@' for notifications.

# CONFIGURATION

## enabled

    /set plugins.var.perl.atcomplete.enabled [on|off]

When set to `off`, this plugin won't add '@' prefixed nicks to the
completion list.

# COPYRIGHT AND LICENSE

Copyright 2015 by David A. Golden. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may
use this file except in compliance with the License. You may obtain
a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
