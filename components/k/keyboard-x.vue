<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjr6nwbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:keyboard-x" /></template>
<style>
.zjr6nwbim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6h13A3.5 3.5 0 0 1 22 9.5v5a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 14.5v-5A3.5 3.5 0 0 1 5.5 6M6 9.25h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01m-7.76 3.25l3.5 3.5m0-3.5l-3.5 3.5");
}

</style>
