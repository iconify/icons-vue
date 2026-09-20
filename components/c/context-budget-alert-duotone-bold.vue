<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c07le3bhf"/><path class="x87wa6b5t"/><path class="lx3jyybfn"/><path class="afo552p2d"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="pfpu_3ppl"/><path class="y1lnycw3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-budget-alert-duotone-bold" /></template>
<style>
.afo552p2d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.c07le3bhf {
  fill: currentColor;
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.lx3jyybfn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x87wa6b5t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y1lnycw3l {
  d: path("M11 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
