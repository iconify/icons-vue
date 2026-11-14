<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtvuf4z5m"/><path class="w4g1icb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:enzyme-catalyst" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rtvuf4z5m {
  d: path("M14.5 8.25V7.5c0-3-2.5-5-5.75-5c-4 0-6.25 4-6.25 9.5s2.25 9.5 6.25 9.5c3.25 0 5.75-2 5.75-5v-.75h-4v-7.5ZM17 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.w4g1icb0p {
  d: path("M13.25 13.75V12H17");
}

</style>
