<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aa2x8_bum"/><path class="vmmpk-o7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forex-chart" /></template>
<style>
.aa2x8_bum {
  d: path("M3.5 3.5v17h17M8 8v9m4-11v9m4-5v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vmmpk-o7v {
  d: path("M6.5 10h3v4h-3Zm4-2h3v4h-3Zm4 4h3v4h-3Z");
}

</style>
