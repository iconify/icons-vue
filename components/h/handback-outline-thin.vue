<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zq_pavbka"/><path class="imjw6lo4s"/><path class="f-l8xfbfx"/><path class="yr5tx9l0o"/><path class="gsf5khfvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:handback-outline-thin" /></template>
<style>
.f-l8xfbfx {
  d: path("M10.5 11H13v2.5");
}

.gsf5khfvc {
  d: path("M16 10a3 3 0 0 1 6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imjw6lo4s {
  d: path("M8.5 15.5 11 13");
}

.yr5tx9l0o {
  d: path("M17 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zq_pavbka {
  d: path("M7.27 15.28a3 3 0 1 1 -2.54 0");
}

</style>
