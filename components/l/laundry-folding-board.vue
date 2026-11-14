<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g33vlsbkl"/><path class="e20ovebdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:laundry-folding-board" /></template>
<style>
.e20ovebdn {
  d: path("M10 6.5a2 2 0 0 0 4 0");
}

.g33vlsbkl {
  d: path("M2.5 12h19M5 12l-1.5 5.5M19 12l1.5 5.5M7.75 6.5h8.5V12h-8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
