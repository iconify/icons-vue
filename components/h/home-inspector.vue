<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1mirc1gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-inspector" /></template>
<style>
.y1mirc1gb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.5a4 4 0 0 1 8 0m-9.5 0h11m-2.211 1.803a3.5 3.5 0 1 1-6.578 0M4 21.5c0-4 3.5-6.25 8-6.25q.95 0 1.831.132m6.123 5.34q.046.377.046.778m-8-19v1.75M14.75 18l2 2L21 15.75");
}

</style>
