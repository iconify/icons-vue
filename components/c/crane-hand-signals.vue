<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9d2jq3tp"/><path class="dqls38bnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crane-hand-signals" /></template>
<style>
.c9d2jq3tp {
  d: path("M3.5 8v8A5.25 5.25 0 0 0 14 16V7.5M7 12V4.5m3.5 7.5V3.5m8 1.5a9 9 0 0 1 0 14");
}

.dqls38bnw {
  d: path("m21.25 18.5l-2.75.5l-.5-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
