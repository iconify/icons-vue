<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lemjmdn8v"/><path class="v8xooabzi"/><path class="ptj3znbqu"/><path class="cf8eb9bym"/><path class="x909-s8qx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:etl-outline-thin" /></template>
<style>
.cf8eb9bym {
  d: path("M18.5 12H22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lemjmdn8v {
  d: path("M2 12h4.5");
}

.ptj3znbqu {
  d: path("M9 9a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.v8xooabzi {
  d: path("m4.5 10 2 2 -2 2");
}

.x909-s8qx {
  d: path("m20 10 2 2 -2 2");
}

</style>
