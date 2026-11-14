<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_pujt-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-putt" /></template>
<style>
.hm_pujt-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 18.5a5.5 2.5 0 1 0 11 0a5.5 2.5 0 1 0-11 0M3.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m9.75.5Q15.5 9 15.5 13");
}

</style>
