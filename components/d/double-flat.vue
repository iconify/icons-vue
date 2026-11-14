<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfzi0xbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:double-flat" /></template>
<style>
.vfzi0xbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3v17.5M5 14c1.5-2.5 5.5-3 5.5 0s-3 5-5.5 6.5M13.5 3v17.5m0-6.5c1.5-2.5 5.5-3 5.5 0s-3 5-5.5 6.5");
}

</style>
