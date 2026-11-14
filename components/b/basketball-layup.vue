<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="el-8_tc4k"/><path class="btwpbfbsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-layup" /></template>
<style>
.btwpbfbsz {
  d: path("M3.75 3.75Q7 7 3.75 10.25m6.5-6.5Q7 7 10.25 10.25M9.5 14h12M11 14l2 7h5l2-7");
}

.el-8_tc4k {
  d: path("M2.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm0 0h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
