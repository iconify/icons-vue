<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bqddp2b0w"/><path class="egybckbbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:animal-cell-detailed" /></template>
<style>
.bqddp2b0w {
  d: path("M2.5 12a9.5 8 0 1 0 19 0a9.5 8 0 1 0-19 0Z");
}

.egybckbbr {
  d: path("M5.75 10.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm7.5 4.5a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
