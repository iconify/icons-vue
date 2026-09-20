<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t9q8gebqk"/><path class="grt7vrw-d"/><path class="s160cgbel"/><path class="bv1y61bvs"/><path class="ils7yp4cg"/><path class="v2r_pnsln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:all-inclusive-duotone-bold" /></template>
<style>
.bv1y61bvs {
  d: path("M4 16a8 8 0 0 1 16 0");
}

.grt7vrw-d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s160cgbel {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 9 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t9q8gebqk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v2r_pnsln {
  d: path("m8 9 3 3 5 -5");
}

</style>
