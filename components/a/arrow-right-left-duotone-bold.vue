<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zl0m38bil"/><path class="xj8x8bc8u"/><path class="rfwgx-bjs"/><path class="kp_n4gbdh"/><path class="jof7c9fpk"/><path class="a6o5bdc8o"/><path class="m-p3hbclp"/><path class="z8bw_gbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-right-left-duotone-bold" /></template>
<style>
.a6o5bdc8o {
  d: path("m16 5 4 4 -4 4");
}

.jof7c9fpk {
  d: path("M4 9h16");
}

.kp_n4gbdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 11 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m-p3hbclp {
  d: path("M4 15h16");
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

.xj8x8bc8u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 5 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z8bw_gbrq {
  d: path("m8 11 -4 4 4 4");
}

.zl0m38bil {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
