<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhvm_3zyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ball-kid" /></template>
<style>
.xhvm_3zyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M3 21c0-3.5 2.25-5.5 5.5-5.5s5.5 2 5.5 5.5m2.5-2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-.25-8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
