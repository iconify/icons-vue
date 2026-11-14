<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9y5dabqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:buffalo" /></template>
<style>
.s9y5dabqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8c0-1 1-1.5 4-1.5S16 7 16 8l-.75 8.5C15 19.5 13.75 21 12 21s-3-1.5-3.25-4.5Zm0 1c-3.5 1.5-5.5-1-5-5m13 5c3.5 1.5 5.5-1 5-5");
}

</style>
