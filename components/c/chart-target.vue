<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wejimtbna"/><path class="l8ln1md9o"/><path class="oxxnebbjv"/><path class="fsbyttsma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-target" /></template>
<style>
.fsbyttsma {
  d: path("m2.5 21.5l3-5.5L8 19l6-9");
}

.l8ln1md9o {
  d: path("M10.5 10a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.oxxnebbjv {
  fill: currentColor;
  d: path("M14 10h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wejimtbna {
  d: path("M6.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

</style>
