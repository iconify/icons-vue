<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d_pdzpb1w"/><path class="be9rdrb3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-curve-down-left" /></template>
<style>
.be9rdrb3n {
  d: path("M13 21H8v-5");
}

.d_pdzpb1w {
  d: path("M16 3v7c0 2-.75 3.75-2 5l-6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
