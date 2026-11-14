<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vm72x7t6g"/><path class="yckmedchu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bio-lab" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vm72x7t6g {
  d: path("m5.533 3.228l.434-.25a1.75 1.75 0 0 1 2.39.64l2.75 4.764a1.75 1.75 0 0 1-.64 2.39l-.434.25a1.75 1.75 0 0 1-2.39-.64l-2.75-4.764a1.75 1.75 0 0 1 .64-2.39");
}

.yckmedchu {
  d: path("M9 20.5c4-1.5 5.5-7.5 2.5-11m-8 5H10m-6.5 6H13m4-6.5v5.5a1.75 1.75 0 0 0 3.5 0V14M16 14h5.5");
}

</style>
