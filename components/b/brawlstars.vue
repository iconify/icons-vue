<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vibcmdb4s"/><path class="n7pvbubiu"/><circle class="mmgtpcfuv"/><path class="ktysdjb-f"/><circle class="aukdtkffl"/><path class="hffhwp6lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brawlstars" /></template>
<style>
.aukdtkffl {
  cx: 31.668px;
  cy: 29.186px;
  r: 5.112px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hffhwp6lz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.305 20.647l-4.02 2.32");
}

.ktysdjb-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.9 17.86l2.321 4.02");
}

.mmgtpcfuv {
  cx: 14.45px;
  cy: 24.573px;
  r: 5.112px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n7pvbubiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.597 33.934l-2.204-.591l-2.204-.59l1.613-1.614l1.614-1.614l.59 2.204Z");
}

.vibcmdb4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.47 33.96c-9.61-7.854-6.365-19.144.928-25.212s17.395-3.24 17.395-3.24s10.163 2.6 13.444 11.503s.447 20.303-11.803 22.299M10.47 33.96l-.711 2.307s-.819 2.092 2.631 2.946l6.877 1.842m11.167-1.745l-.537 2.352s-.337 2.222-3.752 1.236l-6.877-1.843");
}

</style>
