<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="su54c4bne"/><path class="mu0i9zbhe"/><path class="abhqbyb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-sandbox-duotone-bold" /></template>
<style>
.abhqbyb0v {
  d: path("M14.54 6.56a6 6 0 1 1 -5.08 0");
}

.mu0i9zbhe {
  d: path("M14 2h5a3 3 0 0 1 3 3v14a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.su54c4bne {
  fill: currentColor;
  d: path("M14 2h5a3 3 0 0 1 3 3v14a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
