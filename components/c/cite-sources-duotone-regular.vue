<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gmyobjb9w"/><path class="lo9yxl6rk"/><path class="qc-1i0btz"/><path class="ex75cacie"/><path class="nyba_zpqc"/><path class="nutam6ble"/><path class="n-7t0yb1r"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cite-sources-duotone-regular" /></template>
<style>
.ex75cacie {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gmyobjb9w {
  fill: currentColor;
  d: path("M17 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lo9yxl6rk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nutam6ble {
  d: path("M17 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nyba_zpqc {
  d: path("M3 8h11");
}

.qc-1i0btz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
