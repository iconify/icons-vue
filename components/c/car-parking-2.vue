<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xquyqhjls"/><path class="c1vb4vbbt"/><circle class="rssaqqp2i"/><circle class="j_1twkb6t"/><path class="a9f78-bnt"/><circle class="ojkez1mxk"/><path class="cyzavgn9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:car-parking-2" /></template>
<style>
.a9f78-bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.923 20.192a2.556 2.556 0 0 0 5.014 0m14.399 0a2.556 2.556 0 0 0 5.014 0");
}

.c1vb4vbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.162 10.25h7.015l7.523 5.591l8.031.765l1.081 1.266l.188 2.321h-9.77m-9.35-4.352h9.82m-.708 2.031h9.82");
}

.cyzavgn9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.35 29.175a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.082.837-.184 1.664-.762 2.172c-1.072.94-4.524 3.476-4.524 3.476h5.3");
}

.j_1twkb6t {
  cx: 9.725px;
  cy: 19.692px;
  r: 2.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ojkez1mxk {
  cx: 38px;
  cy: 30.75px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rssaqqp2i {
  cx: 29.367px;
  cy: 19.692px;
  r: 2.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xquyqhjls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.03 20.193h2.2l-.238-2.321l-1.081-1.266l-8.031-.765l-3.643-5.591h-8.162l-5.038 5.327l-4.43 1.108L3 19.586l.633.607h3.534m5.327 0h14.262m-1.876-4.352l-16.843-.264m11.568-5.327l-.783 5.479m-5.747-5.479l-.78 5.377");
}

</style>
