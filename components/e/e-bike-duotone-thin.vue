<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzs9k3h2v"/><path class="cqvq03bab"/><path class="emz0wrb2f"/><path class="jfpnmxb4i"/><path class="sebrrz16i"/><path class="pw20x6b3h"/><path class="a5wqubblo"/><path class="s8wcv9b9d"/><path class="ah7e-ybxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:e-bike-duotone-thin" /></template>
<style>
.a5wqubblo {
  d: path("M10 7v4");
}

.ah7e-ybxc {
  d: path("M10 14h5v3h-5Z");
}

.cqvq03bab {
  fill: currentColor;
  d: path("M14 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.emz0wrb2f {
  fill: currentColor;
  d: path("M10 14h5v3h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfpnmxb4i {
  d: path("M2 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.pw20x6b3h {
  d: path("m6 15 4 -4h4l4 4");
}

.s8wcv9b9d {
  d: path("M7.5 7h5");
}

.sebrrz16i {
  d: path("M14 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.xzs9k3h2v {
  fill: currentColor;
  d: path("M2 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
