<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbqgll2bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chopsticks-rest" /></template>
<style>
.vbqgll2bl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 8.75l19-3m-19 6l19-3M8 13.5q4 1.5 8 0a2.5 2.5 0 0 1 0 5q-4-1.5-8 0a2.5 2.5 0 0 1 0-5Z");
}

</style>
