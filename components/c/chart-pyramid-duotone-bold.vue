<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="swxhvqb7v"/><path class="q7zfvpbhn"/><path class="rfwgx-bjs"/><path class="g91uwsb-i"/><path class="y4k_22w_l"/><path class="v9il_wb-q"/><path class="m-p3hbclp"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-pyramid-duotone-bold" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.g91uwsb-i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.q7zfvpbhn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rfwgx-bjs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.swxhvqb7v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v9il_wb-q {
  d: path("M6 10h12");
}

.y4k_22w_l {
  d: path("M8 5h8");
}

</style>
