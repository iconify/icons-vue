<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq7-tt8gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:location-approximate" /></template>
<style>
.pq7-tt8gp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 6.738 4.896m1.02 3.138a9.5 9.5 0 0 1-2.574 7.921m-2.669 1.94a9.5 9.5 0 0 1-8.33 0m-2.669-1.94a9.5 9.5 0 0 1-2.574-7.921m1.02-3.138a9.5 9.5 0 0 1 6.738-4.896");
}

</style>
