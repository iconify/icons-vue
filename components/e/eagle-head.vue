<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2y274-rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eagle-head" /></template>
<style>
.u2y274-rs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5c-1.5-4.5-2-9-1-12.5c1-4 4-6 7.5-6c2 0 3.5.75 4.5 1.75c3 .75 5 3.25 5 6.25c0 1.25-.5 2.25-1.5 2.75c0-1.25-.75-2-2-2h-2.5C14 14 13 17.5 13 21.5m-3.75-14l6 1m-2.75 2.25h.01");
}

</style>
