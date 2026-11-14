<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2q1_abkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fishing-quota" /></template>
<style>
.s2q1_abkc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6V4h18v2M4 15c3-4.5 9-4.5 11.5 0l4.5-3.5v7L15.5 15C13 19.5 7 19.5 4 15m4.5-.5h.01");
}

</style>
