<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fffd9ib1u"/><path class="e2rc6ibxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chromatogram" /></template>
<style>
.e2rc6ibxb {
  d: path("M5 20.5C6.75 20.5 6.75 8 7.75 8s1 12.5 2.75 12.5c1.5 0 1.5-7 2.5-7s1 7 2.5 7s1.5-16 2.5-16s1 16 2.75 16");
}

.fffd9ib1u {
  d: path("M3 3v17.5h18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
