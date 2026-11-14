<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p7r4cbb7y"/><path class="oaqids5ed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consent-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oaqids5ed {
  d: path("m7.5 12.5l3 3l6-7");
}

.p7r4cbb7y {
  d: path("M10.5 3.5h3a7 7 0 0 1 7 7v3a7 7 0 0 1-7 7h-3a7 7 0 0 1-7-7v-3a7 7 0 0 1 7-7");
}

</style>
