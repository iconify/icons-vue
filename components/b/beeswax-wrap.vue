<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iml9c5bhw"/><path class="gehpesouz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beeswax-wrap" /></template>
<style>
.gehpesouz {
  d: path("M16.5 4.5V7H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iml9c5bhw {
  d: path("m3.5 13l2-8.5h11L19 7l1.5 6ZM5 13c0 4 3 6.5 7 6.5s7-2.5 7-6.5");
}

</style>
