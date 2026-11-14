<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6t-mdbow"/><path class="qlmr8fbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-base" /></template>
<style>
.e6t-mdbow {
  d: path("M2.5 15.5v-4a9.5 7 0 0 1 19 0v4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qlmr8fbah {
  d: path("M7.5 15.5V11h9v4.5M4 19.5h3.5m2.75 0h3.5m2.75 0H20");
}

</style>
