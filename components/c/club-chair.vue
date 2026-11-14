<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a_j1v6y2o"/><path class="xhh9a108p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:club-chair" /></template>
<style>
.a_j1v6y2o {
  d: path("M2.5 4.5h19V17h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhh9a108p {
  d: path("M7 17v-5a1.5 1.5 0 0 1 1.5-1.5h7A1.5 1.5 0 0 1 17 12v5M5 17v3.5M19 17v3.5");
}

</style>
