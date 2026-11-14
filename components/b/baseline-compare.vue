<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v_ui7pbkk"/><path class="brt_95bdw"/><path class="m6qduebcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baseline-compare" /></template>
<style>
.brt_95bdw {
  fill: currentColor;
  d: path("M14.75 3.5h3a1.75 1.75 0 0 1 1.75 1.75v14A1.75 1.75 0 0 1 17.75 21h-3A1.75 1.75 0 0 1 13 19.25v-14a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6qduebcm {
  d: path("M4.5 11.5V11a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v.5m-6 1.75V15m6-1.75V15m-6 1.75v1.75m6-1.75v1.75");
}

.v_ui7pbkk {
  d: path("M2.5 21h19");
}

</style>
