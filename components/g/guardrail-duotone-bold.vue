<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q80kgo3im"/><path class="kidjoqbxn"/><path class="wcq6hm3gi"/><path class="tkeq0bpvv"/><path class="yw-dgs_nk"/><path class="ivdpkbnwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guardrail-duotone-bold" /></template>
<style>
.ivdpkbnwt {
  d: path("m11 9 3 3 -3 3");
}

.kidjoqbxn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q80kgo3im {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tkeq0bpvv {
  d: path("M18 4v16");
}

.wcq6hm3gi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m11 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yw-dgs_nk {
  d: path("M4 12h10");
}

</style>
