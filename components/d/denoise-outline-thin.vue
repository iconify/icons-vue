<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z35tx4bdc"/><path class="mqnae981n"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:denoise-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqnae981n {
  d: path("m9 11 3 3 3 -3");
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.z35tx4bdc {
  d: path("m3 6 4 -4 4 4 4 -4 4 4");
}

</style>
