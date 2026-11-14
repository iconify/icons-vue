<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7kjypd0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-accessories" /></template>
<style>
.l7kjypd0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5.5H10A3.5 3.5 0 0 1 13.5 9v6a3.5 3.5 0 0 1-3.5 3.5H6.5A3.5 3.5 0 0 1 3 15V9a3.5 3.5 0 0 1 3.5-3.5m7 4H19l2.5 2.5l-2.5 2.5h-5.5M3 12h7.5m6.5 0h.01");
}

</style>
