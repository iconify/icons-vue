<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apn2llajr"/><path class="nb2sxzb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:led-bulb-leaf" /></template>
<style>
.apn2llajr {
  d: path("M9 16.5C6.5 15 5 12.75 5 10a7 7 0 0 1 14 0c0 2.75-1.5 5-4 6.5V18H9Zm.5 4.5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nb2sxzb8l {
  d: path("M9.5 13c-.25-3.5 2-5.5 5.25-5.75C15 10.5 12.75 13 9.5 13");
}

</style>
