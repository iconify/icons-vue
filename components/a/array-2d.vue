<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6mnfu9_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:array-2d" /></template>
<style>
.t6mnfu9_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.5h-2v19h2m15-19h2v19h-2M6.75 5.25H9a1.5 1.5 0 0 1 1.5 1.5V9A1.5 1.5 0 0 1 9 10.5H6.75A1.5 1.5 0 0 1 5.25 9V6.75a1.5 1.5 0 0 1 1.5-1.5m8.25 0h2.25a1.5 1.5 0 0 1 1.5 1.5V9a1.5 1.5 0 0 1-1.5 1.5H15A1.5 1.5 0 0 1 13.5 9V6.75a1.5 1.5 0 0 1 1.5-1.5M6.75 13.5H9a1.5 1.5 0 0 1 1.5 1.5v2.25a1.5 1.5 0 0 1-1.5 1.5H6.75a1.5 1.5 0 0 1-1.5-1.5V15a1.5 1.5 0 0 1 1.5-1.5m8.25 0h2.25a1.5 1.5 0 0 1 1.5 1.5v2.25a1.5 1.5 0 0 1-1.5 1.5H15a1.5 1.5 0 0 1-1.5-1.5V15a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
