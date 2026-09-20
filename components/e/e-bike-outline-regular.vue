<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jfpnmxb4i"/><path class="sebrrz16i"/><path class="pw20x6b3h"/><path class="a5wqubblo"/><path class="s8wcv9b9d"/><path class="ah7e-ybxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:e-bike-outline-regular" /></template>
<style>
.a5wqubblo {
  d: path("M10 7v4");
}

.ah7e-ybxc {
  d: path("M10 14h5v3h-5Z");
}

.jfpnmxb4i {
  d: path("M2 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

</style>
