<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yprnc_z1f"/><rect class="yv2oy81lw"/><g class="y9tr6bcfx"><path class="u57bxxb3b"/><path class="qykds6r1n"/></g><circle class="gtpbadbak"/><path class="mgfa4bbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imo" /></template>
<style>
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yprnc_z1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.126 2.5 2.5 12.126 2.5 24c0 5.49 2.075 10.484 5.462 14.283c-.971 2.801-2.994 3.675-5.462 4.567c2.26 2.182 6.668 2.76 10.623-.327A21.37 21.37 0 0 0 24 45.5c11.874 0 21.5-9.626 21.5-21.5S35.874 2.5 24 2.5");
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
