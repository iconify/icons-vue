<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="sq39s8bbt"/><path class="wy82zvb7r"/><path class="oneq6edbm"/><circle class="kl2dbjb0g"/><circle class="sh8fj1bhq"/><path class="l-68r4b9d"/><path class="iz4xn-bla"/><circle class="xr4e9bcql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:datafolder" /></template>
<style>
.iz4xn-bla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.018 36.6l-4.845-4.649l-5.979 4.649");
}

.kl2dbjb0g {
  cx: 9.726px;
  cy: 28.229px;
  r: 1.687px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l-68r4b9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.791 15.906l-7.619-4.399v8.798zM20.326 39.062l6.955-4.337l3.907 3.829");
}

.oneq6edbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.947 13.978V7.38a1.88 1.88 0 0 1 1.88-1.88H40.76c1.034 0 1.88.846 1.88 1.88v15.932a1.88 1.88 0 0 1-1.88 1.88h-.743m-21.254-4.097l-7.35 1.019v-2.6l7.35-1.019zm0 0v5.023m-7.35-4.004v6.115");
}

.sh8fj1bhq {
  cx: 17.077px;
  cy: 26.118px;
  r: 1.687px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sq39s8bbt {
  width: 19.691px;
  height: 19.691px;
  x: 20.326px;
  y: 22.809px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.88px;
  ry: 1.88px;
}

.wy82zvb7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.325 33.67H7.24a1.88 1.88 0 0 1-1.88-1.88V15.858c0-1.034.846-1.88 1.88-1.88h15.932a1.88 1.88 0 0 1 1.88 1.88v6.955");
}

.xr4e9bcql {
  cx: 27.163px;
  cy: 29.916px;
  r: 2.031px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
