<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="ozxfy8bzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-area-stacked" /></template>
<style>
.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.ozxfy8bzl {
  d: path("M7 16.5v-3l4-2l3.5 1.5l4-3v6.5Zm0-7l4-3l3.5 2l4-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
