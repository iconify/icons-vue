<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zts2h6bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dimension" /></template>
<style>
.zts2h6bxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 15.75h9.145a1.75 1.75 0 0 1 1.081.374l1.274 1.001a1.75 1.75 0 0 1 0 2.75l-1.274 1.001a1.75 1.75 0 0 1-1.081.374H5.25A1.75 1.75 0 0 1 3.5 19.5v-2a1.75 1.75 0 0 1 1.75-1.75m9.5 2.75h.01m-9.51-4.25l6.75-4l4.5.75l-1.25 3.25m-2-1.25h.01M3 14l3.75-6.75L11 5.5l.5 3.5m-2.25-.25h.01");
}

</style>
