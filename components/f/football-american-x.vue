<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-_dadz5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:football-american-x" /></template>
<style>
.n-_dadz5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.5C3 9 9 3 17.5 3c0 8.5-6 14.5-14.5 14.5Zm5.25-5.25l4-4m-4 2l2 2m0-4l2 2m3.25 5.25l5 5m0-5l-5 5");
}

</style>
