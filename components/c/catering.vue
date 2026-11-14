<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg8-8mdkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:catering" /></template>
<style>
.fg8-8mdkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5c0-4 15-4 15 0m-17 0h19l-1.5 4H4Zm1.5 4L3 20m17-9.5l1 9.5m-9-6.5c2.5 2.5 2.5 6 0 6s-2.5-3.5 0-6");
}

</style>
