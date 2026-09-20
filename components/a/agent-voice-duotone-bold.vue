<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g_1_9obcn"/><path class="zcgemjbtm"/><path class="lj0arfbhi"/><path class="dxqp15kpa"/><path class="g_ig5r7qc"/><path class="os75hg6rr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-voice-duotone-bold" /></template>
<style>
.dxqp15kpa {
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
}

.g_1_9obcn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g_ig5r7qc {
  d: path("M17.12 9.88a3 3 0 0 1 0 4.24");
}

.lj0arfbhi {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.24 7.76a6 6 0 0 1 0 8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.os75hg6rr {
  d: path("M19.24 7.76a6 6 0 0 1 0 8.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zcgemjbtm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.12 9.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
