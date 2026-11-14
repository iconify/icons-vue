<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wrfih64wm"/><path class="qga5ceb-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eyepiece" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qga5ceb-a {
  d: path("M8.5 7v9h7V7M10 16v5.5h4V16");
}

.wrfih64wm {
  d: path("M8.204 2.5h7.592A1.447 1.447 0 0 1 17 4.75l-.98 1.471A1.75 1.75 0 0 1 14.563 7H9.437a1.75 1.75 0 0 1-1.457-.779L7 4.75A1.447 1.447 0 0 1 8.204 2.5");
}

</style>
