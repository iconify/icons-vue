<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b_ob72hqs"/><path class="zamec3bwb"/><path class="qqmuifbpe"/><path class="g91uwsb-i"/><path class="gonglubgb"/><path class="cjsg0ab2y"/><path class="n48oibb_x"/><path class="mf-afdped"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landslide-duotone-bold" /></template>
<style>
.b_ob72hqs {
  fill: currentColor;
  d: path("M10 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cjsg0ab2y {
  d: path("M2 20h20");
}

.g91uwsb-i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gonglubgb {
  d: path("m2 6 6 6h6l6 6");
}

.mf-afdped {
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n48oibb_x {
  d: path("M10 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qqmuifbpe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 6 6 6h6l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zamec3bwb {
  fill: currentColor;
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
