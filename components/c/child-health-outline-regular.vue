<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t_m3g48-w"/><path class="hy1q78bil"/><path class="m0_70pbcq"/><path class="k1llj9blt"/><path class="f2m4wubik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:child-health-outline-regular" /></template>
<style>
.f2m4wubik {
  d: path("M13 12h8");
}

.hy1q78bil {
  d: path("M8 9v5");
}

.k1llj9blt {
  d: path("M17 8v8");
}

.m0_70pbcq {
  d: path("m4 19 5 -5 5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t_m3g48-w {
  d: path("M5 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
