<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gckae0brv.css';
import '../../css/b/bnrd1xfao.css';
import '../../css/r/r17wey2jw.css';
import '../../css/s/ss-bu_bnf.css';
import '../../css/i/i64xizi4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gckae0brv wm-k"/><path class="bnrd1xfao wm-a"/><path class="r17wey2jw wm-shadow"/><path class="ss-bu_bnf wm-k"/><path class="i64xizi4g wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bot-engrave" /></template>
