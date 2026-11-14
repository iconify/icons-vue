<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjd_9pnqk"/><path class="z1mrc3b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:e-moped" /></template>
<style>
.fjd_9pnqk {
  d: path("M12.5 15.5L10 4.5H6A3.5 3.5 0 0 0 2.5 8v7.5H18M15.5 3l3 15m-5-15h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1mrc3b2u {
  d: path("M4 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M8.25 7.5L6 10.25h2.75l-2 2.5");
}

</style>
