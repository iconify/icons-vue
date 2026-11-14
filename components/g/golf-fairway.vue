<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfwy8vbrv"/><path class="t3dv0mbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-fairway" /></template>
<style>
.dfwy8vbrv {
  d: path("M3 21.5C3.5 15 9 11 14.5 9.5A2.75 2.75 0 0 1 19 12c-4.5 1.5-6.5 5-5.5 9.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3dv0mbcb {
  d: path("M8 21.5c.5-5 3.5-8 7.5-9.5m.75-3V3l4.25 1.5L16.25 6");
}

</style>
