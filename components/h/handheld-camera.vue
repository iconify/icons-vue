<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwiwo-98c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handheld-camera" /></template>
<style>
.dwiwo-98c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7h6a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 3 12.5v-2A3.5 3.5 0 0 1 6.5 7m11.25 1.5h1.5A1.75 1.75 0 0 1 21 10.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 16 12.75v-2.5a1.75 1.75 0 0 1 1.75-1.75M5 7V4h5v3m-2.5 9v4.5H12V16");
}

</style>
