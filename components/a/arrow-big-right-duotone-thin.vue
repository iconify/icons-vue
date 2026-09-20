<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nvjd9lbtc"/><path class="yg-bsbc2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-big-right-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nvjd9lbtc {
  fill: currentColor;
  d: path("m21 12 -9 9v-5H3V8h9V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yg-bsbc2q {
  d: path("m21 12 -9 9v-5H3V8h9V3Z");
}

</style>
