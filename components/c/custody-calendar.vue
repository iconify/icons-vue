<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qnj07mblb"/><path class="aiofikbzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:custody-calendar" /></template>
<style>
.aiofikbzs {
  fill: currentColor;
  d: path("M6.5 11.5h3v3h-3Zm8 4.25h3v3h-3Z");
}

.qnj07mblb {
  d: path("M3 4h18v17.5H3Zm5-1.5v3m8-3v3m-13 3h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
