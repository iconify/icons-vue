<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jtkvb9fgt.css';
import '../../css/q/qxgopybcq.css';
import '../../css/g/gri0ybjpd.css';
import '../../css/y/yb8pm2b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jtkvb9fgt"/><path class="qxgopybcq"/><path class="gri0ybjpd"/><path class="yb8pm2b6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-sparkles-sharp-two-tone" /></template>
