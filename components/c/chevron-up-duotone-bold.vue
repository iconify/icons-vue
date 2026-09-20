<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jyn_n-bic"/><path class="sbpsi82ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-up-duotone-bold" /></template>
<style>
.jyn_n-bic {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 15 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sbpsi82ym {
  d: path("m5 15 7 -7 7 7");
}

</style>
