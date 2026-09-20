<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jt4-jw3vg"/><path class="d3aifgicn"/><path class="tfp7g2vbw"/><path class="skbifdbcx"/><path class="p87z9hb2j"/><path class="x3u_7ebsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-upgrade-duotone-bold" /></template>
<style>
.d3aifgicn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 16 4.5 -4.5L21 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jt4-jw3vg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p87z9hb2j {
  d: path("m12 16 4.5 -4.5L21 16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

.tfp7g2vbw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 20.5 4.5 -4.5 4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3u_7ebsy {
  d: path("m12 20.5 4.5 -4.5 4.5 4.5");
}

</style>
