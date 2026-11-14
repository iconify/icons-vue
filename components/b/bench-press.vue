<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcti4lb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bench-press" /></template>
<style>
.jcti4lb3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.5V12m0 3v6M17 5.5V12m0 3v6M2.5 5.5h19M4 3v5m16-5v5M5 12h14a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 19 15H5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 5 12m7 3v6");
}

</style>
