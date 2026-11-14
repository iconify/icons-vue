<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h55m4roek"/><path class="ohqwhib9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biosafety-cabinet" /></template>
<style>
.h55m4roek {
  d: path("M3 3h18v15H3Zm2.5 15v3.5m13-3.5v3.5M3 8.5h18m-9 2.75v4");
}

.ohqwhib9c {
  d: path("M9.75 13L12 15.25L14.25 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
