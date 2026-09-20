<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ys1yigyvq"/><path class="wwnijrnro"/><path class="b1gzncccy"/><path class="lew9i9byp"/><path class="i-zd2i_hi"/><path class="lgr612izs"/><path class="s4ceatb9m"/><path class="kz0kcyi2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breadcrumb-collapse-duotone-regular" /></template>
<style>
.b1gzncccy {
  fill: currentColor;
  d: path("M13 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i-zd2i_hi {
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kz0kcyi2y {
  d: path("m17 8 4 4 -4 4");
}

.lew9i9byp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lgr612izs {
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s4ceatb9m {
  d: path("M13 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.wwnijrnro {
  fill: currentColor;
  d: path("M8 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ys1yigyvq {
  fill: currentColor;
  d: path("M3 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
