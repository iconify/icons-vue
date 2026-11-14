<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u0jbkt1nl"/><path class="gcrbf-bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ev-car-full" /></template>
<style>
.gcrbf-bcg {
  d: path("M5 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 5h5a1 1 0 0 1 1 1v.75h1v1.5h-1v.75a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u0jbkt1nl {
  d: path("M5 11.5H2.5v-4l3.5-1l2.5-4h6l3 4l4 1v4H19m-4 0H9");
}

</style>
