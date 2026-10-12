<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ixfmy2crh"/><path class="j52lqni1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backgammon-sharp" /></template>
<style>
.ixfmy2crh {
  d: path("M2.75 4h18.5v16H2.75z");
}

.j52lqni1d {
  d: path("m5 4l1.75 6L8.5 4l1.75 6L12 4l1.75 6l1.75-6l1.75 6L19 4M5 20l1.75-6l1.75 6l1.75-6L12 20l1.75-6l1.75 6l1.75-6L19 20");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
