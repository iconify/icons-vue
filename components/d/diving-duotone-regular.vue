<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gl2wyfu4j"/><path class="srhmoyb4s"/><path class="wr7w9yb-h"/><path class="ynmv7uyhh"/><path class="d3ptn-bxh"/><path class="qj_kcbc2q"/><path class="q686vz2zk"/><path class="intk4nbhb"/><path class="g1wm5cc6f"/><path class="d147n4bfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:diving-duotone-regular" /></template>
<style>
.d147n4bfy {
  d: path("M3 20c3 -2 6 2 9 0s6 2 9 0");
}

.d3ptn-bxh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20c3 -2 6 2 9 0s6 2 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g1wm5cc6f {
  d: path("m16 15 -3 3");
}

.gl2wyfu4j {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.intk4nbhb {
  d: path("M16 10v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qj_kcbc2q {
  d: path("M3 6h10");
}

.srhmoyb4s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wr7w9yb-h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ynmv7uyhh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 15 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
