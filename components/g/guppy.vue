<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qba-3x_5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guppy" /></template>
<style>
.qba-3x_5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c0-3.5 3-5 6-5s4.5 2.5 5 5c-.5 2.5-2 5-5 5s-6-1.5-6-5m11 0l6.5-6.5c1.5 3 1.5 10 0 13Zm-7.5-1h.01");
}

</style>
