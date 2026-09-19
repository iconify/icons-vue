<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcp19gs0t"/><path class="nib_ozbir"/><g class="y9tr6bcfx"><circle class="lb_wfesqj"/><circle class="zpc1_1p3u"/><circle class="nh54z9bhl"/><circle class="fgkprnb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-play-games" /></template>
<style>
.fgkprnb1j {
  cx: 22.498px;
  cy: 24px;
  r: 1.35px;
}

.lb_wfesqj {
  cx: 19.349px;
  cy: 27.15px;
  r: 1.35px;
}

.nh54z9bhl {
  cx: 16.198px;
  cy: 24px;
  r: 1.35px;
}

.nib_ozbir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.661 31.822h10.688l4.076 5.859M8.661 16.178h10.297a8 8 0 0 1 7.708 5.857L30 33.626");
}

.pcp19gs0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.055 27.738c1.35-.727 2.284-2.18 2.284-3.738c-.104-1.557-1.038-3.01-2.388-3.738h0L15.202 5.623C14.58 5.208 13.75 5 12.918 5C10.945 5 9.18 6.35 8.765 8.115h0c-.104.311-.104.727-.104 1.142v29.59c0 .415 0 .727.104 1.142v-.104h0C9.285 41.65 10.945 43 12.918 43q1.245 0 2.18-.623h0z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zpc1_1p3u {
  cx: 19.349px;
  cy: 20.85px;
  r: 1.35px;
}

</style>
