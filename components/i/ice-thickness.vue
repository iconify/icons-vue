<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhq3nw4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-thickness" /></template>
<style>
.tjhq3nw4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5H15v9H2.5Zm17 0v9m-1.5-9h3M18 9h3m-3 4.5h3M2.5 18q2.25-1.5 4.75 0Q9.5 19.5 12 18q2.25-1.5 4.75 0q2.25 1.5 4.75 0");
}

</style>
