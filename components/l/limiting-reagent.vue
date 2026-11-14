<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgw0_xb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:limiting-reagent" /></template>
<style>
.sgw0_xb-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5L3 4v15a1.5 1.5 0 0 0 1.5 1.5h4A1.5 1.5 0 0 0 10 19V3.5m3.5 0l.5.5v15a1.5 1.5 0 0 0 1.5 1.5h4A1.5 1.5 0 0 0 21 19V3.5m-18 13h7m4-9h7");
}

</style>
