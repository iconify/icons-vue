<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="m_skd9-0z"/><circle class="g3j0pmbqh"/><circle class="m0_yn3osv"/><path class="v6v6e984f"/><path class="a-d4qjbjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:biomass" /></template>
<style>
.a-d4qjbjg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 6.25c.2-2.5 1.2-3.5 4-3.5c-.2 2.5-1.2 3.5-4 3.5");
}

.g3j0pmbqh {
  cx: 17.75px;
  cy: 17.75px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_skd9-0z {
  cx: 6.25px;
  cy: 17.75px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0_yn3osv {
  cx: 12px;
  cy: 10px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6v6e984f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 17.75h.01m11.49 0h.01M12 10h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
