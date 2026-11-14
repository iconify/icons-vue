<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpib-bcvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:corn-field" /></template>
<style>
.dpib-bcvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19M5 21V8m0 8q-2-3.5-2.5-1M5 13c2.5-1 3.25-4 2.5-6C5.75 8 5 10 5 13m7 8V2.5M12 16q-2.5-3.5-3.5-1m3.5-4c2.5-1 3.25-4 2.5-6c-1.75 1-2.5 3-2.5 6m7 10V8m0 8q-2.5-3.5-3.5-1m3.5-2c2-1 2.75-3.5 2.25-5.5c-1.5 1-2.25 3-2.25 5.5");
}

</style>
