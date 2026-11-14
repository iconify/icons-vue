<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn29-_b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-column-banner" /></template>
<style>
.xn29-_b8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.358 6h1.284a1.31 1.31 0 0 0 1.233-1.75l-.269-.755A1.5 1.5 0 0 0 8.193 2.5h-.386a1.5 1.5 0 0 0-1.413.995l-.269.755A1.31 1.31 0 0 0 7.358 6M8 6v15.5m-2.5 0h5M8 9h10m-7 0v10l3.5-2.5L18 19V9");
}

</style>
