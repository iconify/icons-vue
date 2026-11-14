<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zryqcyxyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-sack" /></template>
<style>
.zryqcyxyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6C5 8.5 4 11 4 14v4.5a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V14c0-3-1-5.5-4.5-8m-7 0L7 2.5q5 1.25 10 0L15.5 6m-7 0h7M4 15h16");
}

</style>
