<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="me9dqjepj"/><path class="jhq2fxlof"/><path class="rsvh7b0ab"/><path class="uk_l5kxob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eraser-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhq2fxlof {
  d: path("m3 15 6 -6h12l-6 6Z");
}

.me9dqjepj {
  fill: currentColor;
  d: path("m3 15 6 -6h12l-6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rsvh7b0ab {
  d: path("M3 15v4h12l6 -6V9");
}

.uk_l5kxob {
  d: path("M9 9v4l-6 6");
}

</style>
