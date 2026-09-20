<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c3jgqg1qu"/><path class="hl_s6tb6j"/><path class="ngaq5_b-w"/><path class="c_mfncbzl"/><path class="rj_yrybsf"/><path class="vndgajb9z"/><path class="axg5c-q0a"/><path class="nzb-j6sxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-model-duotone-bold" /></template>
<style>
.axg5c-q0a {
  d: path("M6 10v2.5h12V10");
}

.c_mfncbzl {
  d: path("M2 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.c3jgqg1qu {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hl_s6tb6j {
  fill: currentColor;
  d: path("M14 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ngaq5_b-w {
  fill: currentColor;
  d: path("M8 17a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nzb-j6sxx {
  d: path("M12 12.5V15");
}

.rj_yrybsf {
  d: path("M14 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vndgajb9z {
  d: path("M8 17a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
