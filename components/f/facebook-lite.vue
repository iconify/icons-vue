<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i0933ib3f"/><circle class="vi_nxfq0r"/><path class="fwub5xy9i"/><path class="hi46sqx1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:facebook-lite" /></template>
<style>
.fwub5xy9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 34.5v8h4");
}

.hi46sqx1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 32.76V9.5c0-2.21-1.79-4-4-4h-29c-2.21 0-4 1.79-4 4v29c0 2.21 1.79 4 4 4h23.26");
}

.i0933ib3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5V18.575a5.075 5.075 0 0 1 5.075-5.075h0c2.498 0 4.057.74 5.126 2.123m-14.5 7.665h10.15");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
