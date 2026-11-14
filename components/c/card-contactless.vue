<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6kuvxqwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-contactless" /></template>
<style>
.l6kuvxqwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 8.5h5.25A2.625 2.625 0 0 1 13 11.125v1.75a2.625 2.625 0 0 1-2.625 2.625h-5.25A2.625 2.625 0 0 1 2.5 12.875v-1.75A2.625 2.625 0 0 1 5.125 8.5M2.5 11H13m2.622-2.521a7.5 7.5 0 0 1 0 7.042m2.428-8.333a10.25 10.25 0 0 1 0 9.624m2.428-10.915a13 13 0 0 1 0 12.206");
}

</style>
