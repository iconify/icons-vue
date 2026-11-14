<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1f-uv_2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:approximately-equal" /></template>
<style>
.j1f-uv_2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.5c2.5-2.25 4.5-2.25 7 0s4.5 2.25 7 0m-14 5c2.5-2.25 4.5-2.25 7 0s4.5 2.25 7 0");
}

</style>
