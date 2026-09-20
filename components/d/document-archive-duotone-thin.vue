<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxow7abeb"/><path class="zhwlonbym"/><path class="abnm6smsv"/><path class="nn6jjh0sm"/><path class="w0sebyb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-archive-duotone-thin" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nn6jjh0sm {
  d: path("M9 10h6v7H9Z");
}

.w0sebyb3m {
  d: path("M9 13.5h6");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zhwlonbym {
  fill: currentColor;
  d: path("M9 10h6v7H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
