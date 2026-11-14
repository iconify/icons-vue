<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zh5lu2b_j"/><path class="ax7wf7w7h"/><path class="ppa03p0co"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-bump" /></template>
<style>
.ax7wf7w7h {
  d: path("M2.5 12H8l6-7h4.5m-16 14H8l6-7h4.5");
}

.ppa03p0co {
  fill: currentColor;
  d: path("M18.25 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zh5lu2b_j {
  d: path("M2.5 5H8l6 14h4.5");
}

</style>
