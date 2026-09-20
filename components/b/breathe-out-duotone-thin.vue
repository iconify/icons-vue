<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6e_qy8ax"/><path class="zey5ebc0a"/><path class="l8unaacgj"/><path class="un7y1tbrs"/><path class="s91z9mxxg"/><path class="x909-s8qx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breathe-out-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8unaacgj {
  d: path("M2 12h5");
}

.s91z9mxxg {
  d: path("M22 12h-5");
}

.un7y1tbrs {
  d: path("m4 10 -2 2 2 2");
}

.x6e_qy8ax {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x909-s8qx {
  d: path("m20 10 2 2 -2 2");
}

.zey5ebc0a {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
