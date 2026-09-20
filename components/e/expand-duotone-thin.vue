<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k2mq_ebec"/><path class="g5fbrnbeu"/><path class="ytess4zqc"/><path class="dwq5gjbne"/><path class="cpjt28hee"/><path class="qbycr98pd"/><path class="vw4ruuxbu"/><path class="o32gc9b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:expand-duotone-thin" /></template>
<style>
.cpjt28hee {
  d: path("M4 10V4h6");
}

.dwq5gjbne {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 20 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g5fbrnbeu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 4 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2mq_ebec {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10V4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o32gc9b6a {
  d: path("m20 20 -6 -6");
}

.qbycr98pd {
  d: path("m4 4 6 6");
}

.vw4ruuxbu {
  d: path("M14 20h6v-6");
}

.ytess4zqc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 20h6v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
