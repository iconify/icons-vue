<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqbnxsmkn"/><path class="h7yhrubgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:half-life" /></template>
<style>
.h7yhrubgy {
  d: path("M7 5.5c2.5 7.5 6 11 13 11.5m-9.5 3v-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqbnxsmkn {
  d: path("M4 3v17h16");
}

</style>
