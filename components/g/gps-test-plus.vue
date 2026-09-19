<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="rbrg2mzrn"/><path class="vlsoxgvay"/><circle transform="rotate(-89.91 16.68 6.305)" class="dwxo_pbjv"/><circle class="nn5y6zyug"/><circle class="zxt_2nbcn"/><circle class="f9ipuxoie"/><circle class="eyl2meeoa"/><path class="h6c73xe0s"/><circle class="mabnd9bos"/><path class="dhyg790_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gps-test-plus" /></template>
<style>
.dhyg790_d {
  d: path("M42.999 37.55h-4.411v4.412H35.01V37.55H30.6v-3.577h4.41v-4.41h3.577v4.41h4.41z");
}

.dwxo_pbjv {
  cx: 16.679px;
  cy: 6.305px;
  r: 3.708px;
}

.eyl2meeoa {
  cx: 25.595px;
  cy: 30.292px;
  r: 3.707px;
}

.f9ipuxoie {
  cx: 9.8px;
  cy: 33.859px;
  r: 3.707px;
}

.h6c73xe0s {
  d: path("M38.092 29.586a3.707 3.707 0 1 1 .502 1.654");
}

.mabnd9bos {
  cx: 30.511px;
  cy: 41.695px;
  r: 3.707px;
}

.nn5y6zyug {
  cx: 34.314px;
  cy: 10.695px;
  r: 3.707px;
}

.rbrg2mzrn {
  d: path("M20.365 6.738c1.075-.21 2.185-.32 3.32-.32c2.814 0 5.47.676 7.814 1.874m5.72 4.718a17.1 17.1 0 0 1 3.651 10.592c0 .756-.053 1.442-.147 2.171M33.69 37.591c-.456.33-.878.587-1.367.871m-5.3 2.002c-1.08.212-2.195.323-3.337.323a17.12 17.12 0 0 1-11.297-4.235m-4.41-5.948c-.967-2.15-1.478-4.492-1.478-7.001c0-1.103.104-2.181.303-3.226m2.337-5.931c1.328-2.105 3.1-3.9 5.184-5.257m8.12 23.061c-4.26-.582-7.497-4.227-7.497-8.648a8.738 8.738 0 1 1 14.356 6.693M11.513 11.473l15.24 15.304m2.361 2.371l4.78 4.8");
}

.vlsoxgvay {
  d: path("M6.502 23.723c34.367.13 34.368 0 34.368 0M13.5 33.996l19.728-19.728m-9.478-7.85V27.09m0 6.43v7.267");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zxt_2nbcn {
  cx: 6.207px;
  cy: 16.705px;
  r: 3.707px;
}

</style>
