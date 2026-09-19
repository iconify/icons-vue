<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vs68ofbmw.css';
import '../../css/f/f1blgkbvx.css';
import '../../css/q/qiltuobnx.css';
import '../../css/p/p5eipvbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="vs68ofbmw"/><path class="f1blgkbvx"/><path class="qiltuobnx"/><path class="p5eipvbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:fm" /></template>
