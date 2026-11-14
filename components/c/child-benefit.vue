<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naiy57bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:child-benefit" /></template>
<style>
.naiy57bhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-2.5 13c0-3.75 2.5-6 6-6s6 2.25 6 6m1-8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-1 8.5c0-2.5 1.5-3.75 3.25-3.75s3.5 1.25 3.5 3.75");
}

</style>
