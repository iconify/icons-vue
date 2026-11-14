<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxxqcben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campsite-full" /></template>
<style>
.xaxxqcben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5L12 2.75m3.349 10.527L9 2.75M2.5 18.5h9.9m-4.15 0l2.25-5l2.018 4.484m2.732.516a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m1-2.25l4.5 4.5");
}

</style>
