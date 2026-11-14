<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbgynn7uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blini" /></template>
<style>
.sbgynn7uq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.5h14a2 2 0 0 1 0 4H5a2 2 0 0 1 0-4m1 0a2 2 0 0 1 0-4h11a2 2 0 0 1 0 4m-8-4a2 2 0 0 1 0-4h8.5a2 2 0 0 1 0 4m-7.5-4c0-3.5 4.5-3.5 4.5 0");
}

</style>
