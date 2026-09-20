<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e8ypp_bew"/><path class="jypkqlawl"/><path class="fxzgi5edp"/><path class="u96naibkq"/><path class="f965_vb7r"/><path class="l4r7s5bzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chat-lock-duotone-bold" /></template>
<style>
.e8ypp_bew {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11.5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f965_vb7r {
  d: path("M8 11a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.fxzgi5edp {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11.5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.jypkqlawl {
  fill: currentColor;
  d: path("M8 11a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l4r7s5bzi {
  d: path("M10 9a2 2 0 0 1 4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u96naibkq {
  d: path("M7 18.5v3l3 -3");
}

</style>
