<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjhxq4qby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:canal-towpath" /></template>
<style>
.jjhxq4qby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5q2.25-2 4.75 0Q9.5 7 12 5q2.25-2 4.75 0Q19 7 21.5 5m-19 5q2.25-2 4.75 0Q9.5 12 12 10q2.25-2 4.75 0q2.25 2 4.75 0m-19 5h19m-18 4.5H7m3.25 0h3.5m3.25 0h3.5");
}

</style>
