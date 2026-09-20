<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-21.248 33.164 22.616)" class="ee2yznbjg"/><path class="yj7g3-m2b"/><path class="pei1_pxbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ad-free" /></template>
<style>
.ee2yznbjg {
  cx: 33.164px;
  cy: 22.616px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.879px;
  ry: 17.083px;
}

.pei1_pxbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.46 37.866c-1.93-.193-4.536-3.185-6.177-7.431c-1.64-4.15-1.737-8.011-.58-9.555m26.349 0l-9.555 8.3c2.8 4.922 6.37 7.818 8.88 6.853c3.088-1.255 3.378-8.011.675-15.153m-1.64-3.764l-9.652 8.396a7 7 0 0 1-.29-.772c-2.895-7.431-2.605-14.38.483-15.635c2.703-.965 6.563 2.51 9.459 8.01ZM19.942 38.06zc0 2.026-1.64 3.57-3.764 3.57s-3.764-1.544-3.764-3.474v-.483");
}

.yj7g3-m2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.026 38.831l-26.928-1.447A5.6 5.6 0 0 1 4.5 31.786c0-1.544.772-3.089 1.737-4.15L25.444 7.657");
}

</style>
