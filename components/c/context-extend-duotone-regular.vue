<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bpqmg-bcl"/><path class="n4-p8bcco"/><path class="rcex2je1b"/><path class="lgt3bbkcq"/><path class="ab69i60qd"/><path class="ba3_hzrsr"/><path class="d_yxl29go"/><path class="qebvfnl4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-extend-duotone-regular" /></template>
<style>
.ab69i60qd {
  d: path("M5.5 4H3v16h2.5");
}

.ba3_hzrsr {
  d: path("M7 12h7");
}

.bpqmg-bcl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d_yxl29go {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

.lgt3bbkcq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 4H21v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n4-p8bcco {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qebvfnl4i {
  d: path("M18.5 4H21v16h-2.5");
}

.rcex2je1b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 9.5 16 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
