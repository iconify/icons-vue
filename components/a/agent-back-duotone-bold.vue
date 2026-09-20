<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vlr0-mv_o"/><path class="s0yrzvbnc"/><path class="xhb4q_tse"/><path class="zhmw1tbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-back-duotone-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s0yrzvbnc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vlr0-mv_o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xhb4q_tse {
  d: path("m10 7 -5 5 5 5");
}

.zhmw1tbis {
  d: path("M18.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>
