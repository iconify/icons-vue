<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m9vadkbmx"/><path class="pnf7szbuz"/><path class="ac_0aabuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crop-photo-sharp" /></template>
<style>
.ac_0aabuh {
  d: path("m9.66 13.87l1.93-2.99l.41-.63l.41.63l1.93 2.99l.41.63h-5.5z");
}

.m9vadkbmx {
  d: path("M6.75 2.75v14.5h14.5");
}

.pnf7szbuz {
  d: path("M2.75 6.75h14.5v14.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
