<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mu0i9zbhe"/><path class="x26a8iq1c"/><path class="x64w0obso"/><path class="d121t138w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grid-2x2-check-outline-thin" /></template>
<style>
.d121t138w {
  d: path("m14 16 2 2 3.5 -3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu0i9zbhe {
  d: path("M14 2h5a3 3 0 0 1 3 3v14a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3h5");
}

.x26a8iq1c {
  d: path("M2 12h20");
}

.x64w0obso {
  d: path("M12 2v20");
}

</style>
