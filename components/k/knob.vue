<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se4n8qbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:knob" /></template>
<style>
.se4n8qbdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6 0l2.25-2.25M5.5 18.5h.01M2.75 12h.01M5.5 5.5h.01M12 2.75h.01M18.5 5.5h.01m2.74 6.5h.01m-2.76 6.5h.01");
}

</style>
