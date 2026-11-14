<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dufd2cdfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backdrop-cloth" /></template>
<style>
.dufd2cdfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18m-16 0L4.5 20q2.75-1.5 5 .5q2.5-2 5 0q2.25-2 5-.5L19 3.5M9.5 7v9.5m5-9.5v9.5");
}

</style>
