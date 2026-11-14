<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy2l2xbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dyslexia-friendly" /></template>
<style>
.qy2l2xbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5v14m0-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0m15-11v14m-6-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
