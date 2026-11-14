<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uqdg99bde"/><path class="fuep0d5rg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-saving-tip" /></template>
<style>
.fuep0d5rg {
  d: path("M9.5 12.5c0-3 2-4.75 5-4.75c0 3-2 4.75-5 4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uqdg99bde {
  d: path("M9 16.5c0-1.75-3-3.25-3-7a6 6 0 0 1 12 0c0 3.75-3 5.25-3 7Zm.5 3.25h5");
}

</style>
