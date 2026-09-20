<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zn9ezhlsa"/><path class="xsc9y4bcd"/><path class="kcq0_061d"/><path class="rq12hnw1n"/><path class="cpjt28hee"/><path class="qbycr98pd"/><path class="vw4ruuxbu"/><path class="o32gc9b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:expand-duotone-regular" /></template>
<style>
.cpjt28hee {
  d: path("M4 10V4h6");
}

.kcq0_061d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 20h6v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o32gc9b6a {
  d: path("m20 20 -6 -6");
}

.qbycr98pd {
  d: path("m4 4 6 6");
}

.rq12hnw1n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m20 20 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vw4ruuxbu {
  d: path("M14 20h6v-6");
}

.xsc9y4bcd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 4 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zn9ezhlsa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10V4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
