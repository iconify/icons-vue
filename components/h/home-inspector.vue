<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcz6lkb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-inspector" /></template>
<style>
.bcz6lkb8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5a4 4 0 0 1 8 0m-9.5 0h11m-2.211 1.803a3.5 3.5 0 1 1-6.578 0M4 21.5c0-4 3.5-6.25 8-6.25q.737 0 1.433.08m6.521 5.392q.046.377.046.778m-8-19v1.75M14.75 18l2 2L21 15.75");
}

</style>
