<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="epmiu-b_h"/><path class="xtuk8fhlv"/><path class="icxsopcyx"/><path class="n3_i3brlm"/><path class="rfpc8ubdp"/><path class="b1ew5xbzw"/><path class="ls68ftbad"/><path class="jvpr04bkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-review-score-duotone-bold" /></template>
<style>
.b1ew5xbzw {
  d: path("M14 13v5");
}

.epmiu-b_h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.icxsopcyx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.5 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jvpr04bkw {
  d: path("M21 15v3");
}

.ls68ftbad {
  d: path("M17.5 9v9");
}

.n3_i3brlm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rfpc8ubdp {
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xtuk8fhlv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
