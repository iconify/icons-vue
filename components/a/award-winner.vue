<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptc58c8_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:award-winner" /></template>
<style>
.ptc58c8_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10V9A5 5 0 0 1 7 9Zm0 2H5.25a2.25 2.25 0 0 0 0 4.5H7m10-4.5h1.75a2.25 2.25 0 0 1 0 4.5H17m-5 4v4m-2.25 0h4.5A1.75 1.75 0 0 1 16 19.75a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 19.75A1.75 1.75 0 0 1 9.75 18");
}

</style>
