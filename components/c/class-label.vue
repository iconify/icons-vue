<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a5nrk-3qo"/><path class="rg1uxtrcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:class-label" /></template>
<style>
.a5nrk-3qo {
  d: path("M6 2.5h4.55a3.5 3.5 0 0 1 2.475 1.025l6 6a3.5 3.5 0 0 1 0 4.95l-4.55 4.55a3.5 3.5 0 0 1-4.95 0l-6-6A3.5 3.5 0 0 1 2.5 10.55V6A3.5 3.5 0 0 1 6 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg1uxtrcw {
  d: path("M5.25 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M8 8h.01");
}

</style>
