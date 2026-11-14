<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uaqdvgble"/><path class="i87ak3cbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyword-difficulty" /></template>
<style>
.i87ak3cbg {
  d: path("M11 16a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.uaqdvgble {
  d: path("M3 16a9 9 0 0 1 18 0m-9 0l4.5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
