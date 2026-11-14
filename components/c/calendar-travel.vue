<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls7_y4asv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calendar-travel" /></template>
<style>
.ls7_y4asv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 19.5H2.5V4H19v7.7M7 2.5V6m7.5-3.5V6m-12 3.5H19m-12.5 4h.01m3.99 0h.01M6.5 17h.01m11.74-2.5v7m-3.5-2.25l3.5-2.25l3.5 2.25m-5.25 2.5l1.75-1l1.75 1");
}

</style>
