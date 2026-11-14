<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ksbtii-5g"/><path class="arzl-3bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-turn-up-left" /></template>
<style>
.arzl-3bao {
  d: path("m3.5 9l4-4l4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksbtii-5g {
  d: path("M20.5 19h-8a5 5 0 0 1-5-5V5");
}

</style>
