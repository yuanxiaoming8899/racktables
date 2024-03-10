<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎！</font></font></h1><a id="user-content-welcome" class="anchor" aria-label="永久链接： 欢迎！" href="#welcome"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢您选择 RackTables 作为您的数据中心管理解决方案！</font></font><a href="https://racktables.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您正在寻找文档或希望发送反馈，请在项目网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上查找相应的链接</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何安装机架表</font></font></h1><a id="user-content-how-to-install-racktables" class="anchor" aria-label="永久链接：如何安装 RackTables" href="#how-to-install-racktables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1. 准备服务器</font></font></h2><a id="user-content-1-prepare-the-server" class="anchor" aria-label="永久链接： 1. 准备服务器" href="#1-prepare-the-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RackTables 使用带有 PHP 的 Web 服务器（7.0 是最低要求版本，7.1 是最低测试版本，7.3 是推荐版本）作为前端，并使用 MySQL/MariaDB 服务器版本 5 或更高版本作为后端。</font><font style="vertical-align: inherit;">RackTables 最常用的 Web 服务器是 Apache httpd。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.1. </font><font style="vertical-align: inherit;">安装 MySQL/MariaDB 服务器</font></font></h3><a id="user-content-11-install-mysqlmariadb-server" class="anchor" aria-label="永久链接：1.1。 安装 MySQL/MariaDB 服务器" href="#11-install-mysqlmariadb-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分配</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么做</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Debian 11</font></font></td>
<td><code>apt-get install mariadb-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软呢帽26</font></font></td>
<td><code>dnf install mariadb-server mariadb</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软呢帽 32</font></font></td>
<td><code>dnf install mariadb-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自由BSD 10</font></font></td>
<td><code>pkg install mysql56-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放SUSE 42.1</font></font></td>
<td><code>zypper install mysql-community-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科学Linux 6</font></font></td>
<td><code>yum install mysql-server mysql</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图18.04</font></font></td>
<td><code>apt-get install mysql-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图20.04</font></font></td>
<td><code>apt-get install mariadb-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图22.04</font></font></td>
<td><code>apt-get install mariadb-server</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RHEL 7</font></font></td>
<td><code>yum install -y mariadb-server mariadb</code></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.2. </font><font style="vertical-align: inherit;">在 MySQL/MariaDB 服务器中启用 Unicode</font></font></h3><a id="user-content-12-enable-unicode-in-the-mysqlmariadb-server" class="anchor" aria-label="永久链接：1.2。 在 MySQL/MariaDB 服务器中启用 Unicode" href="#12-enable-unicode-in-the-mysqlmariadb-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分配</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么做</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Debian 11</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需执行任何操作，默认配置为 UTF-8。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软呢帽 26-32</font></font></td>
<td><code>printf "[mysqld]\ncharacter-set-server=utf8\n" &gt; /etc/my.cnf.d/mysqld-charset.cnf; systemctl restart mariadb</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放SUSE 42.1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需执行任何操作，默认配置为 UTF-8。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科学Linux 6</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将行添加</font></font><code>character-set-server=utf8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到文件</font></font><code>[mysqld]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分</font></font><code>/etc/my.cnf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并重新启动 mysqld</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图18.04</font></font></td>
<td><code>printf "[mysqld]\ncharacter-set-server=utf8\n" &gt; /etc/mysql/conf.d/charset.cnf; service mysql restart</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图20.04</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需执行任何操作，默认配置为 UTF-8。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RHEL 7</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将行添加</font></font><code>character-set-server=utf8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到文件</font></font><code>[server]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分</font></font><code>/etc/my.cnf.d/server.cnf</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并重新启动 mysqld</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.3. </font><font style="vertical-align: inherit;">安装 PHP 和 Apache httpd（或 nginx）</font></font></h3><a id="user-content-13-install-php-and-apache-httpd-or-nginx" class="anchor" aria-label="永久链接：1.3。 安装 PHP 和 Apache httpd（或 nginx）" href="#13-install-php-and-apache-httpd-or-nginx"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分配</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么做</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Debian 11</font></font></td>
<td><code>apt-get install apache2-bin libapache2-mod-php php-gd php-mysql php-mbstring php-bcmath php-json php-snmp &amp;&amp; systemctl restart apache2</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软呢帽 26-32</font></font></td>
<td><code>dnf install httpd php php-mysqlnd php-pdo php-gd php-snmp php-mbstring php-bcmath</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自由BSD 10</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">见注释1.3.c</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放SUSE 42.1</font></font></td>
<td><code>zypper install apache2-mod_php5 php5-gd php5-mbstring php5-mysql php5-bcmath</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">科学Linux 6</font></font></td>
<td><code>yum install httpd php php-mysql php-pdo php-gd php-mbstring php-bcmath</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 任何版本</font></font></td>
<td><code>apt-get install apache2-bin libapache2-mod-php php-gd php-mysql php-mbstring php-bcmath php-json php-snmp</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RHEL 7</font></font></td>
<td><code>subscription-manager repos --enable=rhel-server-rhscl-7-rpms</code></td>
</tr>
<tr>
<td></td>
<td><code>yum install httpd24 rh-php70 rh-php70-php-mysqlnd rh-php70-php-pdo rh-php70-php-gd rh-php70-php-snmp rh-php70-php-mbstring rh-php70-php-bcmath rh-php70-php-ldap rh-php70-php</code></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.3.a. </font><font style="vertical-align: inherit;">[已编辑]</font></font></h4><a id="user-content-13a-redacted" class="anchor" aria-label="永久链接：1.3.a。 [已编辑]" href="#13a-redacted"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.3.b. </font><font style="vertical-align: inherit;">[已编辑]</font></font></h4><a id="user-content-13b-redacted" class="anchor" aria-label="永久链接：1.3.b。 [已编辑]" href="#13b-redacted"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.3.c. </font><font style="vertical-align: inherit;">自由BSD 10</font></font></h4><a id="user-content-13c-freebsd-10" class="anchor" aria-label="永久链接：1.3.c。 自由BSD 10" href="#13c-freebsd-10"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过 3 种不同的方式在 FreeBSD 上安装 RackTables 及其依赖项。</font></font></p>
<div class="markdown-heading" dir="auto"><h6 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A.使用pkg（二进制包管理）（并不总是最新版本）</font></font></h6><a id="user-content-a-use-pkg-binary-package-management-not-always-the-newest-version" class="anchor" aria-label="永久链接：A.使用pkg（二进制包管理）（并不总是最新版本）" href="#a-use-pkg-binary-package-management-not-always-the-newest-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># pkg install racktables
# pkg install mod_php56 mysql56-server
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# pkg install racktables
# pkg install mod_php56 mysql56-server" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截至 2017 年 3 月，这将安装 RackTables 版本 0.20.11 及其依赖项（php 5.6、mysql-server 5.6 和 apache 2.4）。</font></font></p>
<div class="markdown-heading" dir="auto"><h6 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B. 使用 ports 系统（可能比 pkg 更新）</font></font></h6><a id="user-content-b-use-the-ports-system-possibly-more-recent-than-pkg" class="anchor" aria-label="永久链接：B. 使用 ports 系统（可能比 pkg 更新）" href="#b-use-the-ports-system-possibly-more-recent-than-pkg"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># cd /usr/ports/sysutils/racktables
# make install
# pkg install mod_php56 mysql56-server
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# cd /usr/ports/sysutils/racktables
# make install
# pkg install mod_php56 mysql56-server" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">截至 2017 年 3 月，这将安装 RackTables 版本 0.20.11 并构建和安装其依赖项（php 5.6、mysql-server 5.6 和 apache 2.4）。</font></font></p>
<div class="markdown-heading" dir="auto"><h6 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C.使用说明书（最新版本）</font></font></h6><a id="user-content-c-manual-newest-version" class="anchor" aria-label="永久链接：C.手册（最新版本）" href="#c-manual-newest-version"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 pkg 安装依赖项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># pkg install php70-bcmath php70-curl php70-filter php70-gd php70-gmp php70-json php70-mbstring php70-openssl php70-pdo php70-pdo_mysql php70-session php70-simplexml php70-snmp php70-sockets
# pkg install mod_php70 mysql56-server
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# pkg install php70-bcmath php70-curl php70-filter php70-gd php70-gmp php70-json php70-mbstring php70-openssl php70-pdo php70-pdo_mysql php70-session php70-simplexml php70-snmp php70-sockets
# pkg install mod_php70 mysql56-server" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 tar.gz/zip 存档解压至</font></font><code>/usr/local/www</code></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">符号链接机架表目录</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># cd /usr/local/www
# ln -s RackTables-0.20.xx racktables
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# cd /usr/local/www
# ln -s RackTables-0.20.xx racktables" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h5 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常见安装步骤</font></font></h5><a id="user-content-common-install-steps" class="anchor" aria-label="永久链接：常见安装步骤" href="#common-install-steps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache 用户应在其 apache Includes 目录下创建一个racktables.conf 文件，其中包含以下内容：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>AddType  application/x-httpd-php         .php
AddType  application/x-httpd-php-source  .phps

&lt;Directory /usr/local/www/racktables/wwwroot&gt;
	DirectoryIndex index.php
	Require all granted
&lt;/Directory&gt;
Alias /racktables /usr/local/www/racktables/wwwroot
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="AddType  application/x-httpd-php         .php
AddType  application/x-httpd-php-source  .phps

<Directory /usr/local/www/racktables/wwwroot>
	DirectoryIndex index.php
	Require all granted
</Directory>
Alias /racktables /usr/local/www/racktables/wwwroot" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动服务：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># echo 'apache24_enable="YES"' &gt;&gt; /etc/rc.conf
# service apache24 start
# echo 'mysql_enable="YES"' &gt;&gt; /etc/rc.conf
# service mysql-server start
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# echo 'apache24_enable=&quot;YES&quot;' >> /etc/rc.conf
# service apache24 start
# echo 'mysql_enable=&quot;YES&quot;' >> /etc/rc.conf
# service mysql-server start" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览至</font></font><a href="http://address.to.your.server/racktables/index.php" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://address.to.your.server/racktables/index.php</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并按照说明进行操作。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font><code>secret.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据提示设置权限。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code># chown www:www /usr/local/www/racktables/wwwroot/inc/secret.php
# chmod 400 /usr/local/www/racktables/wwwroot/inc/secret.php
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# chown www:www /usr/local/www/racktables/wwwroot/inc/secret.php
# chmod 400 /usr/local/www/racktables/wwwroot/inc/secret.php" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.3.d. </font><font style="vertical-align: inherit;">RHEL 7</font></font></h4><a id="user-content-13d-rhel-7" class="anchor" aria-label="永久链接：1.3.d。 RHEL 7" href="#13d-rhel-7"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache 配置和 webroot 位于 /opt/rh/httpd24/root/ 下</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.复制文件</font></font></h2><a id="user-content-2-copy-the-files" class="anchor" aria-label="永久链接：2.复制文件" href="#2-copy-the-files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 tar.gz/zip 存档解压到您选择的目录，并将 Apache httpd 配置为使用</font></font><code>wwwroot</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">子目录作为新的 DocumentRoot。</font><font style="vertical-align: inherit;">另外，到现有 DocumentRoot</font></font><code>wwwroot</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或什至</font></font><code>index.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从现有 DocumentRoot 建立符号链接也是可能的，并且通常是可取的（请参阅 参考资料</font></font><code>README.Fedora</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3.运行安装程序</font></font></h2><a id="user-content-3-run-the-installer" class="anchor" aria-label="永久链接：3.运行安装程序" href="#3-run-the-installer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打开配置的 RackTables URL，系统将提示您配置和初始化应用程序。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分配</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache httpd UID:GID</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MySQL/MariaDB UNIX 套接字路径</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Debian 11</font></font></td>
<td><code>www-data:www-data</code></td>
<td><code>/run/mysqld/mysqld.sock</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软呢帽 26-32</font></font></td>
<td><code>apache:apache</code></td>
<td><code>/var/lib/mysql/mysql.sock</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放SUSE 42.1</font></font></td>
<td><code>wwwrun:www</code></td>
<td><code>/var/run/mysql/mysql.sock</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图18.04</font></font></td>
<td><code>www-data:www-data</code></td>
<td><code>/var/run/mysqld/mysqld.sock</code></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图20.04</font></font></td>
<td><code>www-data:www-data</code></td>
<td><code>/var/run/mysqld/mysqld.sock</code></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何升级 RackTables</font></font></h1><a id="user-content-how-to-upgrade-racktables" class="anchor" aria-label="永久链接：如何升级 RackTables" href="#how-to-upgrade-racktables"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol start="0" dir="auto">
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在实际开始升级之前，</font><strong><font style="vertical-align: inherit;">备份您的数据库并检查下面的发行说明。</font></strong></font></li>
<li><font style="vertical-align: inherit;"></font><code>inc/secret.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">删除除配置（文件）和本地插件（目录中）</font><font style="vertical-align: inherit;">之外的所有现有文件</font></font><code>plugins/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将新的 tar.gz/zip 存档的内容放入该位置。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在浏览器中打开 RackTables 页面。</font><font style="vertical-align: inherit;">软件将检测版本不匹配并显示一条消息，告知您以管理员身份登录以完成升级。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执行此操作并向错误跟踪器或邮件列表报告任何错误。</font></font></li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发行说明</font></font></h2><a id="user-content-release-notes" class="anchor" aria-label="永久链接：发行说明" href="#release-notes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.22.0</font></font></h3><a id="user-content-upgrading-to-0220" class="anchor" aria-label="永久链接：升级到 0.22.0" href="#upgrading-to-0220"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自此版本起，支持的最低 PHP 版本为 7.0。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.21.2</font></font></h3><a id="user-content-upgrading-to-0212" class="anchor" aria-label="永久链接：升级到 0.21.2" href="#upgrading-to-0212"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此版本放弃了对</font></font><code>$localreports</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全局变量的支持，如果需要，在本地插件中替换该全局变量很简单。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>addJS()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和功能</font><font style="vertical-align: inherit;">已分离，</font></font><code>addCSS()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以轻松识别资源使用情况。</font><font style="vertical-align: inherit;">原来的</font></font><code>addJS()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>addCSS()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数很可能会在 0.22.0 中被删除，因为它们已被弃用。</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><em><code>addJSText()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/</font></font><code>addCSSText()</code></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些函数应用于添加未在单独文件中定义的内联 JS/CSS。</font></font></p>
</li>
<li>
<p dir="auto"><em><code>addJSInternal()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/</font></font><code>addCSSInternal()</code></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些函数应用于添加对 JS/CSS 文件的内部引用，该文件可使用</font></font><code>?module=chrome&amp;uri=</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自托管 JS/CSS 文件进行访问。</font><font style="vertical-align: inherit;">这可以被核心和插件使用。</font></font></p>
</li>
<li>
<p dir="auto"><em><code>addJSExternal()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/</font></font><code>addCSSExternal()</code></em></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些函数应用于向托管在外部站点或 CDN 上的 JS/CSS 文件添加外部引用。</font><font style="vertical-align: inherit;">这可以被核心和插件使用。</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这些函数中的每一个都期望第一个参数是数据或 URI，第二个参数是可选组。</font><font style="vertical-align: inherit;">默认情况下，该组设置为“默认”，并且组按字母顺序排序。</font><font style="vertical-align: inherit;">需要注意的是，该</font></font><code>addJSInternal()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数在使用时，还会添加 jQuery 和 RackTables 常用 JavaScript 函数。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于这种分离，您将不再需要提供 TRUE 或 FALSE 来识别参数值是文本还是 URI。</font><font style="vertical-align: inherit;">如果重命名现有的</font></font><code>addJS()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">/</font></font><code>addCSS()</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数调用，请务必删除此参数。</font><font style="vertical-align: inherit;">如果不这样做，则意味着您实际上是在说组名称为“”（假）或“1”（真）。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.21.0</font></font></h3><a id="user-content-upgrading-to-0210" class="anchor" aria-label="永久链接：升级到 0.21.0" href="#upgrading-to-0210"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从现在开始，可以运行 RackTables 的最低（最旧）PHP 版本是 5.5.0。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此版本引入了新的插件架构。</font><font style="vertical-align: inherit;">如果升级后遇到问题，请尝试禁用插件。</font><font style="vertical-align: inherit;">请参阅</font></font><a href="http://wiki.racktables.org/index.php/Plugins" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://wiki.racktables.org/index.php/Plugins</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
了解更多信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到 0.20.11</font></font></h3><a id="user-content-upgrading-to-02011" class="anchor" aria-label="永久链接：升级到 0.20.11" href="#upgrading-to-02011"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引入了新的</font></font><code>IPV4_TREE_SHOW_UNALLOCATED</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置选项，以禁用在 IPv4 空间树中显示未分配的网络。</font><font style="vertical-align: inherit;">设置它也会禁用“骑士”功能。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.20.7</font></font></h3><a id="user-content-upgrading-to-0207" class="anchor" aria-label="永久链接：升级到 0.20.7" href="#upgrading-to-0207"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从现在开始，可以运行 RackTables 的最低（最旧）PHP 版本是 5.2.10。</font><font style="vertical-align: inherit;">特别是，要继续在 CentOS 5 上运行 RackTables，需要在升级之前将其 php* RPM 软件包替换为相应的 php53* 软件包（PHP 5.3 内部提供的 JSON 软件包除外）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据库触发器用于某些数据一致性措施。</font><font style="vertical-align: inherit;">数据库用户帐户必须具有“TRIGGER”权限，该权限是在 MySQL 5.1.7 中引入的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置</font></font><code>IPV4OBJ_LISTSRC</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项被重置为一个表达式，该表达式可为除列出的对象类型之外的所有对象类型启用 IP 寻址功能。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在可以使用具有自动完成功能的文本输入在“编辑/属性”选项卡上分配标签。</font><font style="vertical-align: inherit;">输入星号“*”可在自动完成菜单中查看完整的标签树。</font><font style="vertical-align: inherit;">如果不再需要老式的“标签”选项卡，则值得将以下行添加到权限脚本中：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>  deny {$tab_tags} # this hides 'Tags' tab
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="  deny {$tab_tags} # this hides 'Tags' tab" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此版本将所有数据库字段的排序规则转换为</font></font><code>utf8_unicode_ci</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">此过程可能需要一些时间，并且如果存在仅字母大小写不同的行，则可能会失败。</font><font style="vertical-align: inherit;">如果发生这种情况，您将在升级报告中看到失败的 SQL 查询，并显示“重复条目”错误消息。</font><font style="vertical-align: inherit;">请随意继续使用您的安装。</font><font style="vertical-align: inherit;">如果需要，您可以消除大小写重复的行并重新应用失败的查询。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.20.6</font></font></h3><a id="user-content-upgrading-to-0206" class="anchor" aria-label="永久链接：升级到 0.20.6" href="#upgrading-to-0206"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新的</font></font><code>MGMT_PROTOS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置选项取代了</font></font><code>TELNET_OBJS_LISTSRC</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、
</font></font><code>SSH_OBJS_LISTSRC</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>RDP_OBJS_LISTSRC</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项（根据需要转换现有设置）。</font></font><code>MGMT_PROTOS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">允许使用 RackCode 过滤器为特定设备列表指定任何管理协议。</font><font style="vertical-align: inherit;">默认值 ( )</font><font style="vertical-align: inherit;">为服务器和</font><font style="vertical-align: inherit;">网络交换机</font></font><code>ssh: {$typeid_4}, telnet: {$typeid_8}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成。</font></font><code>ssh://server.fqdn</code><font style="vertical-align: inherit;"></font><code>telnet://switch.fqdn</code><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.20.5</font></font></h3><a id="user-content-upgrading-to-0205" class="anchor" aria-label="永久链接：升级到 0.20.5" href="#upgrading-to-0205"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此版本引入了 VS 组功能。</font><font style="vertical-align: inherit;">VS 组是一种存储和显示虚拟服务配置的新方法。</font><font style="vertical-align: inherit;">有一个新的“ipvs”（VS 组）领域。</font><font style="vertical-align: inherit;">所有以前存在的 VS 配置仍然有效，用户可以自由地将其转换为新格式，以更自然的方式显示它并允许生成 virtual_server_group keepalived 配置。</font><font style="vertical-align: inherit;">要将虚拟服务转换为新格式，需要手动创建VS组对象并为其分配IP地址。</font><font style="vertical-align: inherit;">VS组将显示“迁移”选项卡以转换旧式VS对象，转换成功后可以将其删除。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">旧式 VS 配置已被</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">弃用</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">它的支持将在未来的主要版本中删除。</font><font style="vertical-align: inherit;">因此强烈建议将其转换为新格式。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.20.4</font></font></h3><a id="user-content-upgrading-to-0204" class="anchor" aria-label="永久链接：升级到 0.20.4" href="#upgrading-to-0204"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，Cisco Catalyst 2960 系列交换机的一些字典项目已重命名，以满足官方 Cisco 分类：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">旧名</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新名字</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-48TT</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-48TT-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-24TC</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-24TC-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-24TT</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-24TT-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-8TC</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960-8TC-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960G-48TC</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960G-48TC-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960G-24TC</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960G-24TC-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960G-8TC</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2960G-8TC-L</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C2960-24</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C2960-24-S</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C2960G-24PC</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C2960-24PC-L</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>DATETIME_FORMAT</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于设置日期和时间输出格式的配置选项现在使用</font><font style="vertical-align: inherit;">不同</font></font><a href="http://php.net/manual/en/function.strftime.php" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
语法。</font><font style="vertical-align: inherit;">升级期间，该选项将重置为默认值，根据 ISO 8601，该值现在为 %Y-%m-%d (YYYY-MM-DD)。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此版本引入了两个新的配置选项：
</font></font><code>REVERSED_RACKS_LISTSRC</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>NEAREST_RACKS_CHECKBOX</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.20.1</font></font></h3><a id="user-content-upgrading-to-0201" class="anchor" aria-label="永久链接：升级到 0.20.1" href="#upgrading-to-0201"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.20.0 版本包含一个错误，该错误会破坏 32 位架构计算机上显示的 IP 网络容量。</font><font style="vertical-align: inherit;">为了解决这个问题，此版本使用了 PHP 的 BC Math 模块。</font><font style="vertical-align: inherit;">这是一个新的要求。</font><font style="vertical-align: inherit;">大多数 PHP 发行版都已启用此模块，但如果您的发行版没有启用 - 您需要重新编译 PHP。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“ipaddress”页面的安全上下文现在包括来自包含 IP 地址的网络的标签。</font><font style="vertical-align: inherit;">这意味着您应该审核您的权限规则，以检查是否存在意外允许基于网络标记集更改 IP 的情况。</font><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>	allow {client network} and {New York}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="	allow {client network} and {New York}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此规则现在不仅允许在 NY 客户端网络上进行任何操作，还允许使用这些网络中包含的 IP 地址进行任何操作。</font><font style="vertical-align: inherit;">要解决此问题，您应该这样更改规则：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>	allow {client network} and {New York} and not {$page_ipaddress}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="	allow {client network} and {New York} and not {$page_ipaddress}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升级到0.20.0</font></font></h3><a id="user-content-upgrading-to-0200" class="anchor" aria-label="永久链接：升级到 0.20.0" href="#upgrading-to-0200"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告：此版本有太多内部更改，其中一些更改等待了一年多才发布。</font><font style="vertical-align: inherit;">因此，这个版本被认为是“BETA”，并且仅推荐给同意牺牲稳定性以换取进步的好奇用户。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机架和行现在作为对象存储在数据库中。</font><font style="vertical-align: inherit;">RackObject 表已重命名为 Object。</font><font style="vertical-align: inherit;">创建 SQL 视图是为了简化自定义报告和脚本的迁移。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新的插件引擎而不是</font></font><code>local.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font><font style="vertical-align: inherit;">要使自己的代码存储在
</font></font><code>local.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作中，必须将</font></font><code>local.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件移动到该</font></font><code>plugins/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中。</font><font style="vertical-align: inherit;">该文件的名称不再重要。</font><font style="vertical-align: inherit;">您还可以在该目录中存储多个文件，按功能分离插件，共享它们并尝试其他人的插件，只需将它们放入</font></font><code>plugins/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录中，不再合并。</font></font></p>
<ul dir="auto">
<li><code>$path_to_local_php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变量不再具有特殊含义。</font></font></li>
<li><code>$racktables_confdir</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">变量现在仅用于搜索</font></font><code>secret.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font></font></li>
<li><code>$racktables_plugins_dir</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个指向</font></font><code>plugins/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录的新的可重写特殊变量。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从该版本开始，可以从其属性选项卡中删除 IP 前缀、VLAN、虚拟服务和 RS 池。</font><font style="vertical-align: inherit;">因此，请检查您的权限规则，以确保不会出现不需要的删除这些对象的情况。</font><font style="vertical-align: inherit;">为了确保这一点，您可以在权限脚本的开头尝试以下代码：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>allow {userid_1} and {$op_del}
deny {$op_del} and ({$tab_edit} or {$tab_properties})
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="allow {userid_1} and {$op_del}
deny {$op_del} and ({$tab_edit} or {$tab_properties})" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此版本的 RackTables 中重写了硬件网关引擎。</font><font style="vertical-align: inherit;">这意味着该文件</font></font><code>gateways/deviceconfig/switch.secrets.php</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不再被使用。</font><font style="vertical-align: inherit;">要获取有关以新方式配置连接属性和凭据的信息，请阅读</font></font><a href="http://wiki.racktables.org/index.php/Gateways" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此内容</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这也意味着最近基于旧 API（由 Ilya Evseev 贡献的 D-Link 交换机和 Linux 网关支持）添加的功能不再起作用，并等待向前移植到新网关 API。</font><font style="vertical-align: inherit;">对此感到抱歉。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此版本中出现了两个新的配置变量：</font></font></p>
<ul dir="auto">
<li><code>SEARCH_DOMAINS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">以逗号分隔的 DNS 域列表，这些域被视为网络的“基础”。</font><font style="vertical-align: inherit;">如果 RackTables 搜索引擎根据您的搜索输入找到多个对象，但只有一个对象的 FQDN 由您的输入和这些搜索域之一组成，您将被重定向到该对象，并且其他结果将被丢弃。</font><font style="vertical-align: inherit;">这种行为从0.19.3开始是无条件的，引起了很多用户的反对。</font><font style="vertical-align: inherit;">所以欢迎这个配置变量。</font></font></li>
<li><code>QUICK_LINK_PAGES</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">以逗号分隔的 RackTables 页面列表，在顶部显示指向它们的链接。</font><font style="vertical-align: inherit;">每个用户都可以有自己的列表。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此外，一些配置变量在此版本中更改了其默认值。</font><font style="vertical-align: inherit;">这意味着如果您将它们设置为以前的默认状态，升级脚本将更改它们的值。</font><font style="vertical-align: inherit;">这可能会带来不便，但却是鼓励用户使用新功能的最有效方法。</font><font style="vertical-align: inherit;">如果这种行为不是您想要的，只需恢复这些变量的值：</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多变的</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">老的</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">新的</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><code>SHOW_LAST_TAB</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td></td>
</tr>
<tr>
<td><code>IPV4_TREE_SHOW_USAGE</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络的使用仍然可以通过点击进行。</font></font></td>
</tr>
<tr>
<td><code>IPV4LB_LISTSRC</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">{$typeid_4}</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">错误的</font></font></td>
<td></td>
</tr>
<tr>
<td><code>FILTER_DEFAULT_ANDOR</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这隐式地启用了动态树收缩的功能。</font></font></td>
</tr>
<tr>
<td><code>FILTER_SUGGEST_EXTRA</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的，我们有额外的逻辑过滤器！</font></font></td>
</tr>
<tr>
<td><code>IPV4_TREE_RTR_AS_CELL</code></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将路由器显示为简单文本，而不是单元格。</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另请注意，</font></font><code>IPV4_TREE_RTR_AS_CELL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了“yes”和“no”之外，变量现在还有第三个特殊值：“none”。</font><font style="vertical-align: inherit;">如果您在 IP 树页面上遇到性能低下的情况，请使用“无”值。</font><font style="vertical-align: inherit;">它将完全禁用对已用/备用 IP 的 IP 范围扫描，并且 IP 树的速度将从根本上提高。</font><font style="vertical-align: inherit;">代价是你根本看不到IP树中的路由器。</font></font></p>
</article></div>
