<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zyr0_hpav"/><path class="f_l0dxb0l"/><path class="y4_6s7b5v"/><path class="kpspt_bpo"/><path class="p8yct170k"/><path class="gtov5m4ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:course-enrol-duotone-bold" /></template>
<style>
.f_l0dxb0l {
  fill: currentColor;
  d: path("m13 16 6 -6 2 2 -6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gtov5m4ly {
  d: path("m13 16 6 -6 2 2 -6 6Z");
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.p8yct170k {
  d: path("M7 12h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.zyr0_hpav {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
