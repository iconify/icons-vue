<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh2128bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brass-oil-lamp" /></template>
<style>
.jh2128bsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 10h14c0 2-3 3-7 3s-7-1-7-3m7 3v5.5M8 21l1.5-2.5h5L16 21Zm4-18.5C10 5 9.75 7.25 12 7.25S14 5 12 2.5");
}

</style>
