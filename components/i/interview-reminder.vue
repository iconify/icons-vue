<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k95l5cbpm"/><path class="qpzl12zbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-reminder" /></template>
<style>
.k95l5cbpm {
  d: path("M3 14.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm2.5 5l-1 2m9-2l1 2M2.959 7.959a9.25 9.25 0 0 1 4.147-2.394");
}

.qpzl12zbk {
  d: path("M9.5 11v3.5l2.25 1.25m5-13.25h3.75a1 1 0 0 1 1 1V7a1 1 0 0 1-1 1h-2l-2 1.5V8h.25a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
