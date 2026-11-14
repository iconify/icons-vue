<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6hv_aczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cobblestone" /></template>
<style>
.k6hv_aczn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h3a3.5 3.5 0 0 1 3.5 3.5A3.5 3.5 0 0 1 9 11H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 4m12.375 0zA3.125 3.125 0 0 1 21.5 7.125v.75A3.125 3.125 0 0 1 18.375 11a3.125 3.125 0 0 1-3.125-3.125v-.75A3.125 3.125 0 0 1 18.375 4m-12.75 9.75za3.125 3.125 0 0 1 3.125 3.125v.75a3.125 3.125 0 0 1-3.125 3.125A3.125 3.125 0 0 1 2.5 17.625v-.75a3.125 3.125 0 0 1 3.125-3.125m9.375 0h3a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5h-3a3.5 3.5 0 0 1-3.5-3.5a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
