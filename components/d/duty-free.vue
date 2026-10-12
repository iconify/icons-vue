<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="b5gij23lr"/><path class="f2gugwg_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:duty-free" /></template>
<style>
.b5gij23lr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 8V6a3 3 0 0 1 6 0v2M6.5 8h11q1.5 0 1.64 1.49l.97 10.27q.14 1.49-1.36 1.49H5.25q-1.5 0-1.36-1.49l.97-10.27Q5 8 6.5 8m3 9.75l5-5");
}

.f2gugwg_t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 12.75h.01m4.49 4.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
