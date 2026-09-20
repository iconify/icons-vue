<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hjy8rqkzo"/><path class="j6v5-qbsu"/><path class="wvg4ydbao"/><path class="kj-obfgou"/><path class="yc921jgtb"/><path class="naeroc6tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compute-duotone-bold" /></template>
<style>
.hjy8rqkzo {
  fill: currentColor;
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j6v5-qbsu {
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.kj-obfgou {
  d: path("M9 22h6");
}

.naeroc6tm {
  d: path("M22 9v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wvg4ydbao {
  d: path("M9 2h6");
}

.yc921jgtb {
  d: path("M2 9v6");
}

</style>
