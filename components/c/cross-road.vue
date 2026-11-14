<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-wxxbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cross-road" /></template>
<style>
.yr-wxxbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5V9H2.5M15 2.5V9h6.5m-19 6H9v6.5M21.5 15H15v6.5m-3-19V6m0 12v3.5M2.5 12H6m12 0h3.5");
}

</style>
