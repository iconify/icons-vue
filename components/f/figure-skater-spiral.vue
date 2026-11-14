<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5_cy7kdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:figure-skater-spiral" /></template>
<style>
.i5_cy7kdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h5v5.5l6 2.5c1.5.5 2 1.5 2 3H6ZM5 17h12.5q2 0 1.5-3M3.5 21.5c4.5-2 10.5-2 17-.5");
}

</style>
