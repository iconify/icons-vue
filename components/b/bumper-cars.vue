<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtan7sb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bumper-cars" /></template>
<style>
.qtan7sb9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 14.5h13.5a2.75 2.75 0 0 1 2.75 2.75A2.75 2.75 0 0 1 18.75 20H5.25a2.75 2.75 0 0 1-2.75-2.75a2.75 2.75 0 0 1 2.75-2.75m-.25 0V9h5l2 3h6a2.5 2.5 0 0 1 2.5 2.5M7.5 9V2.5m6 9.5L15 9.5");
}

</style>
