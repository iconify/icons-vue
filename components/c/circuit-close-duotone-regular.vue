<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ylas06exf"/><path class="gob4qybps"/><path class="nztbnjbvs"/><path class="pe38pmb3s"/><path class="sw8cph7mb"/><path class="c4e1y7wvc"/><path class="h36909btm"/><path class="rzbbkyb0w"/><path class="a76nyxbck"/><path class="l0v-b4kbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:circuit-close-duotone-regular" /></template>
<style>
.a76nyxbck {
  d: path("M18 14v5");
}

.c4e1y7wvc {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gob4qybps {
  fill: currentColor;
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h36909btm {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l0v-b4kbr {
  d: path("M8 12h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nztbnjbvs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pe38pmb3s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rzbbkyb0w {
  d: path("M6 5v5");
}

.sw8cph7mb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ylas06exf {
  fill: currentColor;
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
