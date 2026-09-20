<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ricsvm5vg"/><path class="p56aeiufb"/><path class="w2-v5h90u"/><path class="u_mz2vbve"/><path class="ricsl-blc"/><path class="wneoubc6n"/><path class="fzby91bau"/><path class="ka7-gu1bd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:broadcast-duotone-thin" /></template>
<style>
.fzby91bau {
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ka7-gu1bd {
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
}

.p56aeiufb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ricsl-blc {
  d: path("M12 12v9");
}

.ricsvm5vg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u_mz2vbve {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w2-v5h90u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wneoubc6n {
  d: path("M7 21h10");
}

</style>
