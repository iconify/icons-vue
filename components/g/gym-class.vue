<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r891rvbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gym-class" /></template>
<style>
.r891rvbxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12h10M5.5 7zA1.5 1.5 0 0 1 7 8.5v7A1.5 1.5 0 0 1 5.5 17A1.5 1.5 0 0 1 4 15.5v-7A1.5 1.5 0 0 1 5.5 7m13 0zA1.5 1.5 0 0 1 20 8.5v7a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-7A1.5 1.5 0 0 1 18.5 7m-16 5H4m16 0h1.5");
}

</style>
