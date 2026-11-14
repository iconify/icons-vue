<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oes_rbbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cafe-au-lait" /></template>
<style>
.oes_rbbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7h14v5a5 5 0 0 1-5 5h-4a5 5 0 0 1-5-5Zm0 1.5A2.25 2.25 0 0 0 5 13m14-4.5a2.25 2.25 0 0 1 0 4.5M8 10h8");
}

</style>
