<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f0a5f8upj"/><path class="yef8t12oi"/><path class="iq_1-2byr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kettlebell-duotone-thin" /></template>
<style>
.f0a5f8upj {
  fill: currentColor;
  d: path("M7 7a8 8 0 1 0 10 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iq_1-2byr {
  d: path("M7.5 6.5a4.5 4.5 0 0 1 9 0");
}

.yef8t12oi {
  d: path("M7 7a8 8 0 1 0 10 0Z");
}

</style>
