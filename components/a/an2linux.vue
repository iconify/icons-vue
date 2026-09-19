<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kivr89m6d"/><ellipse class="qmcstfbty"/><path class="hj7g9ibuv"/><path class="fdz95i-4e"/><ellipse class="ub16v700n"/><path class="iv-mhjbto"/><circle class="d2xbvcc4y"/><circle class="u7rf4dh_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:an2linux" /></template>
<style>
.d2xbvcc4y {
  cx: 21.39px;
  cy: 21.37px;
  r: 0.75px;
  fill: currentColor;
}

.fdz95i-4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.05 28.85s-6.12 3.76-7.3 3.76s-7.3-3.76-7.3-3.76");
}

.hj7g9ibuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.75 36.78h17.84l-9.2-6.39a4.16 4.16 0 0 1-1.8-3.39v-6.85c0-3.16-1.27-6.8-6.84-6.8c-5.91 0-6.85 3.64-6.85 6.8V27a4.18 4.18 0 0 1-1.79 3.43l-9.2 6.39h17.84");
}

.iv-mhjbto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.75 26.25c3.28 0 4 .22 4 .43c0 1.06-3.12 2.42-4 2.42s-4-1.36-4-2.42c-.01-.21.71-.43 4-.43m-5.91 10.53a5.91 5.91 0 0 0 11.81 0");
}

.kivr89m6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.38 34.55V22.24A14.42 14.42 0 0 0 28.06 8.43a4 4 0 0 0 .06-.6a4.15 4.15 0 0 0-8.3 0a4 4 0 0 0 .06.6A14.42 14.42 0 0 0 9.56 22.24v12");
}

.qmcstfbty {
  cx: 21.39px;
  cy: 20.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.36px;
  ry: 3.21px;
}

.u7rf4dh_q {
  cx: 26.11px;
  cy: 21.37px;
  r: 0.75px;
  fill: currentColor;
}

.ub16v700n {
  cx: 26.11px;
  cy: 20.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.36px;
  ry: 3.21px;
}

</style>
