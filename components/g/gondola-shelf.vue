<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hekew5b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gondola-shelf" /></template>
<style>
.hekew5b_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h1.5A1.5 1.5 0 0 1 7 4v16a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20V4A1.5 1.5 0 0 1 4 2.5M8.25 19h12a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-12A1.25 1.25 0 0 1 7 20.25A1.25 1.25 0 0 1 8.25 19M7 4h14.5M7 10h14.5M7 15.5h14.5m-11-9zA1.5 1.5 0 0 1 12 8v.5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 9 8.5V8a1.5 1.5 0 0 1 1.5-1.5m5.5 0zA1.5 1.5 0 0 1 17.5 8v.5A1.5 1.5 0 0 1 16 10a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 16 6.5m-5.5 6h1A1.5 1.5 0 0 1 13 14a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 9 14a1.5 1.5 0 0 1 1.5-1.5m7-.5za1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 16 14v-.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
