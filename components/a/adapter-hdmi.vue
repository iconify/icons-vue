<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfnqsccql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adapter-hdmi" /></template>
<style>
.nfnqsccql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h17v4.5L17 12H7L3.5 8.5Zm6.37 8h4.26a1.5 1.5 0 0 1 1.464 1.825l-.333 1.5a1.5 1.5 0 0 1-1.464 1.175h-3.594a1.5 1.5 0 0 1-1.464-1.175l-.333-1.5A1.5 1.5 0 0 1 9.87 12M12 16.5v5M7.5 7h9");
}

</style>
