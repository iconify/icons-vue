<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5beyjd8g"/><path class="inp0fub_p"/><path class="ci4x5ab7x"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:client-duotone-thin" /></template>
<style>
.ci4x5ab7x {
  d: path("M5.5 17h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.inp0fub_p {
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.t7ql4f28h {
  d: path("m19 10 2 2 -2 2");
}

.x5beyjd8g {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zy54a7bml {
  d: path("M17 12h4");
}

</style>
