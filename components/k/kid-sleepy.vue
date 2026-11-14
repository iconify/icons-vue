<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6w80t3od"/><path class="k7j2s4mko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kid-sleepy" /></template>
<style>
.k7j2s4mko {
  d: path("M6.25 13.5q1.25 1.5 2.5 0m2.5 0q1.25 1.5 2.5 0");
}

.l6w80t3od {
  d: path("M3.25 14.75a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0ZM20 2.5a3 3 0 1 0 1 4a2.5 2.5 0 0 1-1-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
