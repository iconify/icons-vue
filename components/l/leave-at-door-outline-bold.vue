<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wt76_hbmn"/><path class="mp_4i_b2x"/><path class="gsl4fcakz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leave-at-door-outline-bold" /></template>
<style>
.gsl4fcakz {
  d: path("m13.5 16 2 2 3 -3");
}

.mp_4i_b2x {
  d: path("M12 14a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

</style>
