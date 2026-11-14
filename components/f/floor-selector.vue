<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jub7f0b8y"/><path class="ymb2htbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-selector" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jub7f0b8y {
  d: path("M5.125 2.5h4.75A2.625 2.625 0 0 1 12.5 5.125v13.75A2.625 2.625 0 0 1 9.875 21.5h-4.75A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5m.125 4.75h4.5M5.25 12h4.5");
}

.ymb2htbzy {
  d: path("M6 21.5V17h3.25v4.5M15 9l3-3l3 3m-6 6l3 3l3-3");
}

</style>
