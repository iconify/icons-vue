<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ryupnmnrb"/><path class="hiu57r88u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:igloo-hotel" /></template>
<style>
.hiu57r88u {
  d: path("M9.5 19v-3c0-2 5-2 5 0v3m-11-6.5h17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ryupnmnrb {
  d: path("M3.5 19C3.5 11 7 6 12 6s8.5 5 8.5 13Z");
}

</style>
