<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="axifanblo"/><circle class="m_6c0ubwy"/><path class="bzy5_itsi"/><circle class="l991b5b6m"/><path class="s1f9ehlgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:limousine" /></template>
<style>
.axifanblo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.48 12.34l.79-.18Q5 12 5.43 11.39l.89-1.28q.43-.61 1.18-.61h8.75q.75 0 1.22.59l1.06 1.32q.47.59 1.2.75l.79.18q.73.16.73.91V16q0 .75-.75.75h-17q-.75 0-.75-.75v-2.75q0-.75.73-.91m1.02-.09h15.75m-12-2.75v2.75M11.5 9.5v2.75m3.25-2.75v2.75");
}

.bzy5_itsi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 19h.01");
}

.l991b5b6m {
  cx: 18.25px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_6c0ubwy {
  cx: 5.75px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1f9ehlgm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 19h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
