<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1frmu7eb"/><path class="z3t48tbyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-bee" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1frmu7eb {
  d: path("M4 14.5a7.5 5.5 0 1 0 15 0a7.5 5.5 0 1 0-15 0");
}

.z3t48tbyi {
  d: path("M11.5 9c-2-5-5-6.5-5.5-4.5C5.75 6 8.5 8 11.5 9m0 0c2-5 5-6.5 5.5-4.5C17.25 6 14.5 8 11.5 9m7.5 5.5h2.5m-13-5v10m6-10v10");
}

</style>
