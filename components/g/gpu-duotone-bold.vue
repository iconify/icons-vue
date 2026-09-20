<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fs7w_vboi"/><path class="bou-hgelm"/><path class="a9xazx6hn"/><path class="o19v3ublc"/><path class="coi-np7dk"/><path class="x2sfcqbvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gpu-duotone-bold" /></template>
<style>
.a9xazx6hn {
  d: path("M14 6h5a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3h5");
}

.bou-hgelm {
  fill: currentColor;
  d: path("M5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.coi-np7dk {
  d: path("M15 9v6");
}

.fs7w_vboi {
  fill: currentColor;
  d: path("M14 6h5a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o19v3ublc {
  d: path("M5 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x2sfcqbvg {
  d: path("M18 9v6");
}

</style>
