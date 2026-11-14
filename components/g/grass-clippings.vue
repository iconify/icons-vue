<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sspn2pb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grass-clippings" /></template>
<style>
.sspn2pb1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19C3 13 8 11 12 11s9 2 9.5 8ZM6 12.75L7.25 9M9 11.5l2-5m1 4.5l1-3m2 3.5L17.5 6");
}

</style>
