<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7lqrbcen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lingerie-department" /></template>
<style>
.y7lqrbcen {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16c0-4.5 2.25-6.5 4.5-6.5s4.5 2 4.5 6.5m0 0c0-4.5 2.25-6.5 4.5-6.5s4.5 2 4.5 6.5M2.5 16h19v2.5h-19Zm5-6.5L6.5 3m10 6.5l1-6.5");
}

</style>
