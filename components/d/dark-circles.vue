<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bdlacrtxm"/><path class="anu3be45f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dark-circles" /></template>
<style>
.anu3be45f {
  d: path("M9.25 8.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6.5 17q5.5 3 11 0M9 21q3 1.5 6 0");
}

.bdlacrtxm {
  d: path("M2.5 8.5C5 4.75 8.25 3 12 3s7 1.75 9.5 5.5C19 12.25 15.75 14 12 14s-7-1.75-9.5-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
