<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y3p9ddc5z"/><path class="gnh8f7r8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electronics-department" /></template>
<style>
.gnh8f7r8f {
  d: path("M18.75 16.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3p9ddc5z {
  d: path("M5.125 4h8.75A2.625 2.625 0 0 1 16.5 6.625v5.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 2.5 11.875v-5.25A2.625 2.625 0 0 1 5.125 4M9.5 14.5V18m-3.5.5h7M19.75 7za1.75 1.75 0 0 1 1.75 1.75v11a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 18 19.75v-11A1.75 1.75 0 0 1 19.75 7m0 3h.01");
}

</style>
