<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="v7xfanbfw"/><path class="q3f0f47al"/><path class="ytpwexbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alert-group-outline-thin" /></template>
<style>
.f4yp5uw0u {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k70w93buq {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

.q3f0f47al {
  d: path("M8.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.v7xfanbfw {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ytpwexbvl {
  d: path("M13.5 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
