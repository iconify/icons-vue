<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9fprfbsw"/><path class="rt61dzi9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dive-knife" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rt61dzi9d {
  d: path("M10.586 13.414za1.75 1.75 0 0 1 0 2.475l-2.829 2.829a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l2.829-2.829a1.75 1.75 0 0 1 2.475 0m5.657-5.657l-3.889 3.889");
}

.t9fprfbsw {
  d: path("m18.541 6.873l-.119 1.069a1.5 1.5 0 0 1-.43.895l-4.931 4.931a1.5 1.5 0 0 1-2.122 0l-.707-.707a1.5 1.5 0 0 1 0-2.122l4.931-4.931a1.5 1.5 0 0 1 .895-.43l1.069-.119a1.28 1.28 0 0 1 1.414 1.414m-10.43 4.066l4.95 4.95");
}

</style>
