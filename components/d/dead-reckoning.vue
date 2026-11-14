<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng42dbcdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dead-reckoning" /></template>
<style>
.ng42dbcdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5h.01M7 17h.01m3.49-3.5h.01M10 10.75h3.25V14m1.25-7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
