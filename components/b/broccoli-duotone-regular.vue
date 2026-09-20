<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s9ivncb1z"/><path class="t2xnbczjm"/><path class="lkivjibuo"/><path class="p6px4qbbr"/><path class="pmv9af26x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:broccoli-duotone-regular" /></template>
<style>
.lkivjibuo {
  d: path("M12 13v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6px4qbbr {
  d: path("M12 16H8");
}

.pmv9af26x {
  d: path("M12 16h4");
}

.s9ivncb1z {
  fill: currentColor;
  d: path("M5 13a4 4 0 0 1 4 -6 4 4 0 0 1 6 0 4 4 0 0 1 4 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t2xnbczjm {
  d: path("M5 13a4 4 0 0 1 4 -6 4 4 0 0 1 6 0 4 4 0 0 1 4 6Z");
}

</style>
