<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="roliryp-r"/><path class="lird3ge_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grab-handle" /></template>
<style>
.lird3ge_j {
  d: path("M7 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.roliryp-r {
  d: path("M2.5 4h19M10.25 4v4.5l1.75 2l1.75-2V4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
