<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wq5i1ab0p"/><path class="nc9trzb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-smell-report" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nc9trzb9w {
  d: path("M8.5 14.25h7a2.25 2.25 0 0 0 0-4.5a3.5 3.5 0 0 0-7 0a2.25 2.25 0 0 0 0 4.5");
}

.wq5i1ab0p {
  d: path("M5 3.5h14a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2h-9l-4.5 4v-4H5a2 2 0 0 1-2-2V5.5a2 2 0 0 1 2-2");
}

</style>
