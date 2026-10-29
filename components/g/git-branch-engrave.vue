<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/spbyornbc.css';
import '../../css/p/pvi2rebjf.css';
import '../../css/c/ce-slac7d.css';
import '../../css/l/l7jhf3bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="spbyornbc"/><path class="pvi2rebjf wm-shadow"/><path class="ce-slac7d"/><path class="l7jhf3bei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-engrave" /></template>
