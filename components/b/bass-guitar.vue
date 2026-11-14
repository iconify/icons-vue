<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0x4t0bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bass-guitar" /></template>
<style>
.j0x4t0bqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14.5a3.5 3.5 0 1 0 3 3a2.5 2.5 0 1 0-3-3m4.25-1.25L18.5 5.5m-.164-1.25l1.414-1.414a1 1 0 0 1 1.414 0a1 1 0 0 1 0 1.414L19.75 5.664a1 1 0 0 1-1.414 0a1 1 0 0 1 0-1.414M5 17l2 2");
}

</style>
