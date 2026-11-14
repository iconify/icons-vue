<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qymz4029i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-low" /></template>
<style>
.qymz4029i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.5h3A3.5 3.5 0 0 1 17 8v10a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 18V8a3.5 3.5 0 0 1 3.5-3.5m-.5-2h4M10 18h4");
}

</style>
