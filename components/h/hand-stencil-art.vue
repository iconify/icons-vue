<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1hq70bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-stencil-art" /></template>
<style>
.o1hq70bju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 11h.5a5.25 5.25 0 0 1 5.25 5.25a5.25 5.25 0 0 1-5.25 5.25h-.5a5.25 5.25 0 0 1-5.25-5.25A5.25 5.25 0 0 1 11.75 11m-3.25.25l-2-6.75m5 6.5V3m3 8l1.75-7m1.25 11.5l3-5M6.5 16L3 12.5");
}

</style>
