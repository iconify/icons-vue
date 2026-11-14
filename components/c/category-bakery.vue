<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jttc3ed9x"/><path class="mjye9w2ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-bakery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jttc3ed9x {
  d: path("M3.5 19.5C1 13 5.5 4.5 12 4.5s11 8.5 8.5 15c-2-5-5-7-8.5-7s-6.5 2-8.5 7");
}

.mjye9w2ln {
  d: path("M7.75 6q0 4 1.25 6.75M16.25 6q0 4-1.25 6.75");
}

</style>
