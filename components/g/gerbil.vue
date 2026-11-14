<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ka5o8gdbz"/><path class="m2ts5uf9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gerbil" /></template>
<style>
.ka5o8gdbz {
  d: path("M5.5 9c0-3 2-4.5 4.5-4.5a2.25 2.25 0 1 1 3.75 2c1.75 1.5 2.75 4.5 2.75 8s-2 6-5 6h-4c1-3.5 1.25-7 1-8.5c-1.5-.5-3-1.5-3-3Zm3-1.25h.01");
}

.m2ts5uf9u {
  d: path("M15.25 18.75C19 19.5 21 16.5 20 13.5c-.5-1.25-1.75-1-2 .25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
