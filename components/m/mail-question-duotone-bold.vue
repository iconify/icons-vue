<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="adpm_c_dx"/><path class="osf2djx3l"/><path class="vizlgibdt"/><path class="im9sid5gw"/><path class="b63apxhzl"/><path class="f_bh4os0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-question-duotone-bold" /></template>
<style>
.adpm_c_dx {
  fill: currentColor;
  d: path("M3 11.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.b63apxhzl {
  d: path("M9.5 14.5A2.5 2.5 0 1 1 12 17");
}

.f_bh4os0e {
  d: path("M11 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.im9sid5gw {
  d: path("m5 9.5 7 -7 7 7");
}

.osf2djx3l {
  fill: currentColor;
  d: path("M11 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vizlgibdt {
  d: path("M3 11.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
