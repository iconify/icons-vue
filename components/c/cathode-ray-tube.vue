<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9er_bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cathode-ray-tube" /></template>
<style>
.gs9er_bfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 4h4.75A2.625 2.625 0 0 1 13 6.625v7.75A2.625 2.625 0 0 1 10.375 17h-4.75A2.625 2.625 0 0 1 3 14.375v-7.75A2.625 2.625 0 0 1 5.625 4M13 6l5.5 3.5H21v3h-2.5L13 15m-5 2v3.5m-3 0h6");
}

</style>
