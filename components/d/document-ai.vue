<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/psiglkazx.css';
import '../../css/j/jvqvxcckb.css';
import '../../css/x/x779ubc8b.css';
import '../../css/m/mx_sis13y.css';
import '../../css/y/ynai27lav.css';
import '../../css/g/g194wjqvo.css';
import '../../css/r/r2x1b_pnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><g transform="translate(5 3)" class="psiglkazx"><path class="jvqvxcckb"/><path class="x779ubc8b"/><circle transform="matrix(1 0 0 -1 0 33)" class="mx_sis13y"/><circle transform="matrix(1 0 0 -1 0 15)" class="ynai27lav"/><circle class="g194wjqvo"/></g><path class="r2x1b_pnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:document-ai" /></template>
