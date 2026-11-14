<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk690tbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:autograph" /></template>
<style>
.nk690tbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15C5 9.5 6.5 6 8 6s.5 8 2 8s2-4.5 3.5-4.5s1 3.5 2.5 3.5c1.25 0 2.5-1.5 4.5-2.5m-17 9h17");
}

</style>
