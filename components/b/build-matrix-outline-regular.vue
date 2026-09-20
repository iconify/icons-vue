<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b0hkzgbgd"/><path class="wuk2mlziz"/><path class="kq98nmbqp"/><path class="rxr8gqf5x"/><path class="m_a9oxi_o"/><path class="y4a8ig_7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:build-matrix-outline-regular" /></template>
<style>
.b0hkzgbgd {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.kq98nmbqp {
  d: path("M8.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.m_a9oxi_o {
  d: path("M8.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rxr8gqf5x {
  d: path("M13.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wuk2mlziz {
  d: path("M7 19h10");
}

.y4a8ig_7t {
  d: path("M13.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
