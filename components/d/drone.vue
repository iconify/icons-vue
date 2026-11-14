<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jo09qob6w"/><path class="koyi_v3dd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo09qob6w {
  fill: currentColor;
  d: path("M11.5 9.75h1a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75");
}

.koyi_v3dd {
  d: path("M9.75 9.75L7.5 7.5m6.75 2.25L16.5 7.5m-2.25 6.75l2.25 2.25m-6.75-2.25L7.5 16.5M2 6a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0m13 0a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0M2 18a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0m13 0a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0");
}

</style>
