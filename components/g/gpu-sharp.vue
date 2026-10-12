<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nftlfbbwt"/><path class="s_kkqzb4i"/><path class="rlq0cwfub"/><path class="u5gt8rbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gpu-sharp" /></template>
<style>
.nftlfbbwt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5v11.5H2.75z");
}

.rlq0cwfub {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11h.01M16 11h.01");
}

.s_kkqzb4i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.25a2.75 2.75 0 1 1 0 5.5a2.75 2.75 0 1 1 0-5.5m8 0a2.75 2.75 0 1 1 0 5.5a2.75 2.75 0 1 1 0-5.5");
}

.u5gt8rbgg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 16.75v3h8.5v-3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
