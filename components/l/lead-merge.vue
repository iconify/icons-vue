<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cnskf9b_e"/><path class="q1gvlsbzv"/><path class="bl0jh46dw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-merge" /></template>
<style>
.bl0jh46dw {
  d: path("M9.25 13.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6 21.5c0-1.75 2.75-2.75 6-2.75s6 1 6 2.75");
}

.cnskf9b_e {
  d: path("M3.25 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m13 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q1gvlsbzv {
  d: path("M5.5 6.75C5.5 9 12 8.25 12 10.5m6.5-3.75C18.5 9 12 8.25 12 10.5");
}

</style>
