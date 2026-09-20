<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cu26jmb_i"/><path class="x50q_4bdr"/><path class="qaa4bo00g"/><path class="j6apg33fy"/><path class="r68i47b4w"/><path class="c6_1lkb2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:booking-cancel-outline-regular" /></template>
<style>
.c6_1lkb2d {
  d: path("m14 13.5 -4 4");
}

.cu26jmb_i {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.j6apg33fy {
  d: path("M16 2.5V5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qaa4bo00g {
  d: path("M8 2.5V5");
}

.r68i47b4w {
  d: path("m10 13.5 4 4");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
