<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0v0kng5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:district-heating-pipe" /></template>
<style>
.y0v0kng5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12.5V16h-8v4.5h19V16h-8v-3.5M7.142 6.975l3.75-3.068a1.75 1.75 0 0 1 2.216 0l3.75 3.068a1.75 1.75 0 0 1 .642 1.354v2.421a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75V8.329a1.75 1.75 0 0 1 .642-1.354");
}

</style>
