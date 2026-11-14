<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvw6uaboz"/><path class="d3dgu_bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:due-date-calendar" /></template>
<style>
.d3dgu_bbg {
  d: path("m12 18l-3-3c-1.25-1.25-.75-3 1-3c1 0 1.5.5 2 1.25c.5-.75 1-1.25 2-1.25c1.75 0 2.25 1.75 1 3Z");
}

.fvw6uaboz {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4M3 9h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
