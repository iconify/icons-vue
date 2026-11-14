<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-62hdc8r"/><path class="sykl6dzdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alert-broadcast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sykl6dzdz {
  d: path("M10.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6.25-3.75a6 6 0 0 1 0 7.5m-9-7.5a6 6 0 0 0 0 7.5M18 14.5V18m0 3h.01");
}

.w-62hdc8r {
  d: path("M8.5 21.5L12 8.75l3.25 11.84");
}

</style>
