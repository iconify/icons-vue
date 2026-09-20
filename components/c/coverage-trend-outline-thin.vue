<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="fs--blxyx"/><path class="xxenxccpt"/><path class="hlt9oudyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coverage-trend-outline-thin" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.fs--blxyx {
  d: path("M9 13v3");
}

.hlt9oudyd {
  d: path("M15 9v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.xxenxccpt {
  d: path("M12 11v5");
}

</style>
