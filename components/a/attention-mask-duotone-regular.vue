<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzsthfbrb"/><path class="dp8rry9sk"/><path class="ujtuebbmd"/><path class="zid7cdc0n"/><path class="nzpsuduik"/><path class="edg0x3nuq"/><path class="xsyfe-byx"/><path class="qfgxpvbvs"/><path class="ehef6tbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attention-mask-duotone-regular" /></template>
<style>
.dp8rry9sk {
  fill: currentColor;
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.edg0x3nuq {
  d: path("m5 5 14 14");
}

.ehef6tbzw {
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mzsthfbrb {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzpsuduik {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.qfgxpvbvs {
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ujtuebbmd {
  fill: currentColor;
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xsyfe-byx {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zid7cdc0n {
  fill: currentColor;
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
