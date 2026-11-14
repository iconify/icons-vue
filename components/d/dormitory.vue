<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="shd3azbcg"/><path class="ieoboacug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dormitory" /></template>
<style>
.ieoboacug {
  d: path("M7 11.5V21m0-6.5h10V21M7 18h10");
}

.shd3azbcg {
  d: path("M3.5 9L12 3l8.5 6v12h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
