<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3yla_b-g"/><rect class="yv2oy81lw"/><path class="dm6av5_wf"/><path class="p-_nxx3oi"/><circle class="gtpbadbak"/><path class="mgfa4bbuq"/><circle class="vi_nxfq0r"/><path class="w588tzbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imo-hd" /></template>
<style>
.dm6av5_wf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.918 22.797a2.909 2.909 0 1 1 5.818 0v4.8m-5.818-7.709v7.709");
}

.gtpbadbak {
  cx: 13.56px;
  cy: 17.179px;
  r: 0.75px;
  fill: currentColor;
}

.m3yla_b-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.327 33.431a21.4 21.4 0 0 0 2.173-9.43c0-11.875-9.626-21.5-21.5-21.5S2.5 12.125 2.5 24c0 5.49 2.075 10.484 5.462 14.283c-.971 2.8-2.994 3.675-5.462 4.567c2.26 2.181 6.668 2.76 10.623-.328A21.37 21.37 0 0 0 24 45.5c3.385 0 6.587-.783 9.436-2.176");
}

.mgfa4bbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.56 19.888v7.709");
}

.p-_nxx3oi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.736 22.797a2.909 2.909 0 1 1 5.818 0v4.8");
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

.w588tzbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.236 34.5v8m5.3-8v8m-5.3-4.015h5.3");
}

.yv2oy81lw {
  width: 5.818px;
  height: 7.709px;
  x: 31.64px;
  y: 19.888px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.909px;
  ry: 2.909px;
}

</style>
