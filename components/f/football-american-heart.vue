<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfmzmyb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:football-american-heart" /></template>
<style>
.lfmzmyb9p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.5C3 9 9 3 17.5 3c0 8.5-6 14.5-14.5 14.5m5.25-5.25l4-4m-4 2l2 2m0-4l2 2m6.25 11C15 18.75 14.75 15 16.75 15c.75 0 1.5.5 1.75 1.25c.25-.75 1-1.25 1.75-1.25c2 0 1.75 3.75-1.75 6.25");
}

</style>
