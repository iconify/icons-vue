<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6gn3ibll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-click-sharp" /></template>
<style>
.g6gn3ibll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.66 8.96l8.93 3.58l1.16.46l-1.19.38l-3.12.99l-1.19.38l-.4 1.19l-.95 2.87l-.4 1.19l-.41-1.18l-3.18-9.14L8.5 8.5zm-4.7 3.08a5 5 0 0 1 7.08-7.08");
}

</style>
