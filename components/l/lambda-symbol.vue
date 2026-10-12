<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><path class="v4kp1obkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lambda-symbol" /></template>
<style>
.f7r42znre {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4kp1obkr {
  d: path("M8 6.75h1.25a1.5 1.5 0 0 1 1.4.97l4.85 9.53h1m-4.75-5.75L8 17.25");
}

</style>
