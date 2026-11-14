<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xaf3lmb0l"/><path class="vnfo6ebmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electron" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnfo6ebmy {
  fill: currentColor;
  d: path("M17.75 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.xaf3lmb0l {
  d: path("M4.25 16.5a9 5-30 1 1 15.5-9a9 5-30 1 1-15.5 9");
}

</style>
