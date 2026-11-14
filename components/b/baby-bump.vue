<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwer21ywc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-bump" /></template>
<style>
.wwer21ywc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5C6.5 6 5 9 5.5 12s1.5 6 1 9.5m4-19c0 2 1.5 3 2 5c.25 1.5-1 1.75-1 2.5c5 .5 7.5 3.5 7 6.5s-3.5 4.5-6 5m3-6h.01");
}

</style>
