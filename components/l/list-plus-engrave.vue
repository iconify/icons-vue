<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/otutvum0e.css';
import '../../css/d/d4oa5vbln.css';
import '../../css/q/qnhnw3b5e.css';
import '../../css/x/xe65wvb-d.css';
import '../../css/c/c3wgojkty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="otutvum0e wm-k"/><path class="d4oa5vbln wm-s"/><path class="qnhnw3b5e wm-shadow"/><path class="wm-k xe65wvb-d"/><path class="c3wgojkty wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-plus-engrave" /></template>
