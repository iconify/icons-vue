<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0rgyga7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atmospheric-river" /></template>
<style>
.j0rgyga7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5C7 5 10 10 14 6c3-3 5-3 7.5-3.5m-19 11C7 9 10 14 14 10c3-3 5-3 7.5-3.5M7 16.5L5.5 20m6.5-4.5L10.5 19m7-6.5L16 16");
}

</style>
