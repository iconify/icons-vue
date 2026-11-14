<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srbrawbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:device-e-waste" /></template>
<style>
.srbrawbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9.5h8a3.5 3.5 0 0 1 3.5 3.5v4.5A3.5 3.5 0 0 1 16 21H8a3.5 3.5 0 0 1-3.5-3.5V13A3.5 3.5 0 0 1 8 9.5m-5-3h18m-11.5 0V4h5v2.5m-5.5 6V18m3-5.5V18m3-5.5V18");
}

</style>
