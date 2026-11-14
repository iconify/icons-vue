<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0jz_cigx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-rest-cushion" /></template>
<style>
.x0jz_cigx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5C8 6 16 6 20.5 7.5q1.5 3 0 6C16 15 8 15 3.5 13.5q-1.5-3 0-6m-1 10h19");
}

</style>
