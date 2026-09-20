<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jb_v2ub8s"/><path class="qad15dc2h"/><path class="l4xxtubsj"/><path class="lezwc4bvo"/><path class="z2peracrj"/><path class="vslz5yb3q"/><path class="xhm9ckc2y"/><path class="gl0vd86ea"/><path class="h26bvabki"/><path class="tmc4aacim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dumbbell-duotone-bold" /></template>
<style>
.gl0vd86ea {
  d: path("M18 7v10");
}

.h26bvabki {
  d: path("M3 9v6");
}

.jb_v2ub8s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l4xxtubsj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lezwc4bvo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qad15dc2h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tmc4aacim {
  d: path("M21 9v6");
}

.vslz5yb3q {
  d: path("M6 12h12");
}

.xhm9ckc2y {
  d: path("M6 7v10");
}

.z2peracrj {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
