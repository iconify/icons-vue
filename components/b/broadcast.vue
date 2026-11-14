<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysvcdq3-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broadcast" /></template>
<style>
.ysvcdq3-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h4.5l7-4.5v15l-7-4.5H3Zm3.5 6l1 4.5M17.564 9.429a4 4 0 0 1 0 5.142M19.862 7.5a7 7 0 0 1 0 9");
}

</style>
