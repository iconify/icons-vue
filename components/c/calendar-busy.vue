<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wocaxlmgc"/><path class="gvcxnfe0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-busy" /></template>
<style>
.gvcxnfe0e {
  fill: currentColor;
  d: path("M6.5 14h11v3h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wocaxlmgc {
  d: path("M3 4.5h18v17H3Zm5-2v4m8-4v4m-13 3h18");
}

</style>
