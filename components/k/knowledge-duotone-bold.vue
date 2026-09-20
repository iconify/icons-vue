<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c_s6h8ded"/><path class="w_lu3fbkz"/><path class="kdybz_aht"/><path class="nuugr4b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:knowledge-duotone-bold" /></template>
<style>
.c_s6h8ded {
  fill: currentColor;
  d: path("M7 9a5 5 0 1 0 10 0A5 5 0 1 0 7 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kdybz_aht {
  d: path("M9 17h6");
}

.nuugr4b2c {
  d: path("M10 20h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w_lu3fbkz {
  d: path("M7 9a5 5 0 1 0 10 0A5 5 0 1 0 7 9");
}

</style>
