<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnq2tit0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-directors-cover" /></template>
<style>
.fnq2tit0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19M4 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5.75-1a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6.25 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5 14v6.5M19 14v6.5M3.25 14c0-2 1.25-3.25 2.75-3.25c1 0 1.75.5 2.25 1.25m.5 2c0-2.25 1.45-3.75 3.25-3.75s3.25 1.5 3.25 3.75m.5-2c.5-.75 1.25-1.25 2.25-1.25c1.5 0 2.75 1.25 2.75 3.25");
}

</style>
