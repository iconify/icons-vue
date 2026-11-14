<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3afzccsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-wire" /></template>
<style>
.j3afzccsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.202 10h11.596a2.625 2.625 0 0 1 2.574 3.14l-.95 4.75A2.625 2.625 0 0 1 16.848 20H7.152a2.625 2.625 0 0 1-2.574-2.11l-.95-4.75A2.625 2.625 0 0 1 6.202 10M7.5 10V8.5a4.5 4.5 0 0 1 9 0V10m-8 3v4m3.5-4v4m3.5-4v4");
}

</style>
