<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug3sp7bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:abdomen" /></template>
<style>
.ug3sp7bbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5c0 4-1.5 6.5-1.5 10s1 6.25 2.5 9m10-19c0 4 1.5 6.5 1.5 10s-1 6.25-2.5 9m-4.5-11h.01M8.5 16l2.75 5m4.25-5l-2.75 5");
}

</style>
