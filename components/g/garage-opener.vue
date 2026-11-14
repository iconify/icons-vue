<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cvdkvvbqf"/><path class="sctshabpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garage-opener" /></template>
<style>
.cvdkvvbqf {
  d: path("M12 9za5 5 0 0 1 5 5v2.5a5 5 0 0 1-5 5a5 5 0 0 1-5-5V14a5 5 0 0 1 5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sctshabpb {
  d: path("M10 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5-9.25a4.5 4.5 0 0 1 5 0m-6.75-2.5a7.5 7.5 0 0 1 8.5 0");
}

</style>
