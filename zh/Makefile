export FOP_CFG=-c book/fop.xconf
include ../tools/Makefile.base

# Customization hooks for xsltproc options

# Customization for the html target
HTML_XSLTPROC_OPTS = --stringparam l10n.gentext.language zh_cn

# Customization for the pdf target
# Examples
# Custom page size: --stringparam page.height 9in --stringparam page.width 6.4in
# Paper type A4: --stringparam paper.type A4
FO_XSLTPROC_OPTS = --param fop1.extensions 1 --stringparam l10n.gentext.language zh_cn

L10N_REVISION = r
