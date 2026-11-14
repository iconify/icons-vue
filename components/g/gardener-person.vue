<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3n42gb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gardener-person" /></template>
<style>
.h3n42gb0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.5h17m-12 0v-3a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3m-6.75 0v1.25a3.25 3.25 0 0 0 6.5 0V8.5M4.5 21c0-3 3.25-5 7.5-5q.302 0 .596.013M18.5 21.5v-4c0-2 1.25-3 3-3c0 2-1.25 3-3 3m0 1.75c0-1.5-1.25-2.5-3.25-2.5c0 1.5 1.25 2.5 3.25 2.5");
}

</style>
