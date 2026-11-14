<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e344zkynq"/><path class="u8hjy9vtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beanie-pompom" /></template>
<style>
.e344zkynq {
  d: path("M5.5 16c0-5.5 2.5-8.25 6.5-8.25s6.5 2.75 6.5 8.25m-15 0h17v5h-17Z");
}

.u8hjy9vtj {
  d: path("M9.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM8.25 16v5M12 16v5m3.75-5v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
