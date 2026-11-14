<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdrp1dfxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:demolition-wall" /></template>
<style>
.mdrp1dfxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.5h4.5A1.75 1.75 0 0 1 11 11.25v7.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 3 18.75v-7.5A1.75 1.75 0 0 1 4.75 9.5M3 13.25h8M3 17h8M7 9.5v3.75M7 17v3.5m7-6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m3.5-11v7.5");
}

</style>
