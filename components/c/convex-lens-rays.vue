<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="as4vzu3je"/><path class="ev2a68btr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:convex-lens-rays" /></template>
<style>
.as4vzu3je {
  d: path("M8.5 3q4 9 0 18q-4-9 0-18Z");
}

.ev2a68btr {
  d: path("M3.5 7.5h5l12 4.5m-17 4.5h5l12-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
