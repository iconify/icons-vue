<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="b0tb8_g4o"/><circle class="f5ybazb2z"/><circle class="nfr8hyb3j"/><circle class="b9cfczb3h"/><circle class="jf3u00bmq"/><circle class="u_opambqw"/><circle class="a1lpsdbvp"/><path class="ee007-b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:heliboard" /></template>
<style>
.a1lpsdbvp {
  cx: 29.247px;
  cy: 24.927px;
  r: 3.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.b0tb8_g4o {
  width: 35.055px;
  height: 5.819px;
  x: 6.685px;
  y: 31.508px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.736px;
  ry: 0.736px;
}

.b9cfczb3h {
  cx: 39.74px;
  cy: 14.433px;
  r: 3.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ee007-b1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.943 10.936v6.995m4.634-6.995v6.995M5.943 14.42h4.634m29.731 10.507a1.749 1.749 0 1 1 0 3.497h-2.885V21.43h2.885a1.749 1.749 0 1 1 0 3.498m0-.001h-2.885");
}

.f5ybazb2z {
  cx: 18.753px;
  cy: 14.433px;
  r: 3.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jf3u00bmq {
  cx: 8.26px;
  cy: 24.927px;
  r: 3.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nfr8hyb3j {
  cx: 29.247px;
  cy: 14.433px;
  r: 3.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u_opambqw {
  cx: 18.753px;
  cy: 24.927px;
  r: 3.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
