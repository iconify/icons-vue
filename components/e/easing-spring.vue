<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppe40tb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:easing-spring" /></template>
<style>
.ppe40tb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c4 0 5-16 8.5-16c3 0 3 5.5 5.5 5.5c2 0 2.5-2.5 5-2.5m-19 13h.01M21.5 7h.01");
}

</style>
