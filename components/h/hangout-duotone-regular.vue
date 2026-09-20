<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqn6j-y8l"/><path class="l46grxbhs"/><path class="gl2wyfu4j"/><path class="uj1augdau"/><path class="d4rfzbb0c"/><path class="q686vz2zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hangout-duotone-regular" /></template>
<style>
.d4rfzbb0c {
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gl2wyfu4j {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l46grxbhs {
  fill: currentColor;
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqn6j-y8l {
  fill: currentColor;
  d: path("M3 12v6h18v-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.uj1augdau {
  d: path("M3 12v6h18v-6Z");
}

</style>
