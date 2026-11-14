<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="povmb_zyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:joggers" /></template>
<style>
.povmb_zyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11A1.5 1.5 0 0 1 19 4a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 4a1.5 1.5 0 0 1 1.5-1.5m-.5 3L6.5 18H10l2-9l2 9h3.5L18 5.5M8.25 18zA1.75 1.75 0 0 1 10 19.75a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 8.25 18m7.5 0za1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 14 19.75A1.75 1.75 0 0 1 15.75 18");
}

</style>
