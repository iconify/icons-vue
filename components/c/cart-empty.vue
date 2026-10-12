<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vborlwbka"/><circle class="fpq61538s"/><circle class="vzw8i56kn"/><path class="rnx_wb5sc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cart-empty" /></template>
<style>
.fpq61538s {
  cx: 9.25px;
  cy: 18.75px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnx_wb5sc {
  d: path("M8 6.25h2.5m2.25 0h2.5m2.25 0h2a1 1 0 0 1 .97 1.24l-.36 1.46m-.51 2l-.33 1.34A2 2 0 0 1 17.33 14h-.83m-2.25 0H12");
}

.vborlwbka {
  d: path("M2.75 3.75h1.4A1.5 1.5 0 0 1 5.61 4.9L7.65 14h2.1");
}

.vzw8i56kn {
  cx: 17.25px;
  cy: 18.75px;
  r: 1.5px;
}

</style>
