<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4iodn2ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:forecast-model" /></template>
<style>
.x4iodn2ee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13.5a3.5 3.5 0 0 1-.5-7a5 5 0 0 1 9-.5a3.75 3.75 0 0 1 .25 7.5Zm12 2.25h2a1.75 1.75 0 0 1 1.75 1.75v2.25A1.75 1.75 0 0 1 20 21.5h-2a1.75 1.75 0 0 1-1.75-1.75V17.5A1.75 1.75 0 0 1 18 15.75m1 0v5.75m-2.75-2.75h5.5");
}

</style>
