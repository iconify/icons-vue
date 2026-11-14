<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4s964b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alfajores" /></template>
<style>
.b4s964b9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5C3 5 21 5 21 9.5Zm0 5h18c0 4-18 4-18 0Zm2-5q-2.5 2.5 0 5m14-5q2.5 2.5 0 5");
}

</style>
