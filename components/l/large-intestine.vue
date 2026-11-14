<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld3_1jbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:large-intestine" /></template>
<style>
.ld3_1jbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19.5Q1.5 17.75 3 16q-1.5-1.75 0-3.5Q1.5 10.75 3 9Q1.5 7.25 3 5.5c0-2 1.25-3 3-3q2-1 4 0q2-1 4 0q2-1 4 0c1.75 0 3 1 3 3q1.5 1.75 0 3.5q1.5 1.75 0 3.5q1.5 1.75 0 3.5q1.5 1.75 0 3.5h-4v-11c0-1.25-.75-2-2-2H9c-1.25 0-2 .75-2 2v11Zm16 0v2.25");
}

</style>
