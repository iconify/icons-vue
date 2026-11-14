<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vce4kux0d"/><path class="b73f24g0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:craft-knife" /></template>
<style>
.b73f24g0s {
  d: path("M11.75 9.75L21 3l-6.75 9.25M7 17l1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vce4kux0d {
  d: path("m2.75 18.75l9-9l2.5 2.5l-9 9Z");
}

</style>
