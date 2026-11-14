<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veo46qx_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hibiscus" /></template>
<style>
.veo46qx_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10.25a3 3 0 1 1 4 0A3 3 0 1 1 14.25 14A3 3 0 1 1 11 16.5A3 3 0 1 1 7.75 14A3 3 0 1 1 9 10.25M11 13l8-8m0 0h.01");
}

</style>
