<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="licl6tbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-conditioner" /></template>
<style>
.licl6tbho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v1A3.5 3.5 0 0 1 18 12H6a3.5 3.5 0 0 1-3.5-3.5v-1A3.5 3.5 0 0 1 6 4m-.5 5h13m-10 6v5.5m-2-2l2 2l2-2m5-3.5v5.5m-2-2l2 2l2-2");
}

</style>
