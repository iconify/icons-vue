<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-1hrwb_m"/><path class="a09ol1o7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blueprint" /></template>
<style>
.a09ol1o7u {
  d: path("M19.5 16.5H16a1.5 1.5 0 0 0-1.5 1.5v3.5M10 12.25H7.5V5.5h9v6.75H13m0-6.75v3.25M7.5 15v3m0-1.5h4m0-1.5v3");
}

.b-1hrwb_m {
  d: path("M4.5 5A2.5 2.5 0 0 1 7 2.5h10A2.5 2.5 0 0 1 19.5 5v11.5l-5 5H7A2.5 2.5 0 0 1 4.5 19Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
