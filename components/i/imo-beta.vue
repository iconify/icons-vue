<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cft0zfb5a"/><rect class="yv2oy81lw"/><g class="y9tr6bcfx"><path class="u57bxxb3b"/><path class="qykds6r1n"/></g><circle class="gtpbadbak"/><path class="mgfa4bbuq"/><circle class="vi_nxfq0r"/><path class="funm8-8nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imo-beta" /></template>
<style>
.cft0zfb5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.327 33.43A21.4 21.4 0 0 0 45.5 24c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24c0 5.49 2.075 10.484 5.462 14.283c-.971 2.801-2.994 3.675-5.462 4.567c2.26 2.182 6.668 2.76 10.623-.327A21.37 21.37 0 0 0 24 45.5a21.4 21.4 0 0 0 9.436-2.176");
}

.funm8-8nd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.536 38.5a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3");
}

.gtpbadbak {
  cx: 13.56px;
  cy: 17.179px;
  r: 0.75px;
  fill: currentColor;
}

.mgfa4bbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.56 19.888v7.709");
}

.qykds6r1n {
  d: path("M22.736 22.797a2.91 2.91 0 0 1 2.909-2.91h0a2.91 2.91 0 0 1 2.909 2.91v4.8");
}

.u57bxxb3b {
  d: path("M16.918 22.797a2.91 2.91 0 0 1 2.909-2.91h0a2.91 2.91 0 0 1 2.909 2.91v4.8m-5.818-7.709v7.709");
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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
