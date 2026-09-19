<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="sf56mebtd"/><ellipse transform="rotate(-61.136 24 24)" class="sf56mebtd"/><path class="d_qxexboe"/><ellipse transform="rotate(-28.864 24 24)" class="xh1vlfbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:electrum" /></template>
<style>
.d_qxexboe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.369 24a2.215 2.215 0 0 1 0 4.43h-3.654v-8.86h3.654a2.215 2.215 0 0 1 0 4.43m0 0h-3.654m0-4.429h-1.299m1.299 8.858h-1.299m2.425-8.858V18m1.808 1.571V18m-1.808 12v-1.571M24.649 30v-1.571");
}

.sf56mebtd {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 9.5px;
}

.xh1vlfbqu {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.5px;
  ry: 19.5px;
}

</style>
