<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-kd5b9-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:comment-pin-top" /></template>
<style>
.l-kd5b9-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14A2.5 2.5 0 0 1 6 11.5h12a2.5 2.5 0 0 1 2.5 2.5v1.5A2.5 2.5 0 0 1 18 18h-8l-2.5 2.5V18H6a2.5 2.5 0 0 1-2.5-2.5ZM12 3.5v5.25M9 6.5l3-3l3 3");
}

</style>
