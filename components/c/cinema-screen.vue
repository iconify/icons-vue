<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1_unvfom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-screen" /></template>
<style>
.u1_unvfom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4q9.5-1.5 19 0v10.5q-9.5-1.5-19 0ZM5 21a3 3 0 0 1 6 0m2 0a3 3 0 0 1 6 0");
}

</style>
