<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ow9nvovdw"/><path class="thz-qac8s"/><path class="lf6jf1bxr"/><path class="yiqwex2_u"/><path class="ksgk5nb8u"/><path class="vtcxv5brk"/><path class="b7nacdcee"/><path class="d223d_x9q"/><path class="d_scobift"/><path class="ymrjh3b_x"/><path class="k2jd848hu"/><path class="f2m4wubik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:answer-synthesis-duotone-regular" /></template>
<style>
.b7nacdcee {
  d: path("M3 6h6");
}

.d_scobift {
  d: path("M3 18h6");
}

.d223d_x9q {
  d: path("M3 12h6");
}

.f2m4wubik {
  d: path("M13 12h8");
}

.k2jd848hu {
  d: path("m9 16 4 -4");
}

.ksgk5nb8u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lf6jf1bxr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ow9nvovdw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.thz-qac8s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vtcxv5brk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yiqwex2_u {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymrjh3b_x {
  d: path("m9 8 4 4");
}

</style>
