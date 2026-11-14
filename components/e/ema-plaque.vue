<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="two3lacvu"/><path class="hnqhecbgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ema-plaque" /></template>
<style>
.hnqhecbgb {
  d: path("M8.5 7.25L12 2.5l3.5 4.75m-5 3.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-3 5h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.two3lacvu {
  d: path("m3.967 9.516l7.25-3.625a1.75 1.75 0 0 1 1.566 0l7.25 3.625A1.75 1.75 0 0 1 21 11.082v6.668a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 17.75v-6.668a1.75 1.75 0 0 1 .967-1.566");
}

</style>
