<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwub5xy9i"/><circle class="vi_nxfq0r"/><path class="mgfa4bbuq"/><circle class="gtpbadbak"/><path class="h7uo3obfl"/><path class="tzexoyb-d"/><path class="owil3u7gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imo-lite" /></template>
<style>
.fwub5xy9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 34.5v8h4");
}

.gtpbadbak {
  cx: 13.56px;
  cy: 17.179px;
  r: 0.75px;
  fill: currentColor;
}

.h7uo3obfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.736 22.797a2.91 2.91 0 0 1 2.908-2.91h.001a2.91 2.91 0 0 1 2.909 2.909v4.801m-11.636-7.71v7.71");
}

.mgfa4bbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.56 19.888v7.709");
}

.owil3u7gt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.327 33.431A21.4 21.4 0 0 0 45.5 24c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24c0 5.49 2.075 10.484 5.462 14.283c-.971 2.801-2.994 3.675-5.462 4.567c2.26 2.182 6.668 2.76 10.623-.327A21.37 21.37 0 0 0 24 45.5c3.385 0 6.587-.782 9.435-2.176");
}

.tzexoyb-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.918 22.797a2.91 2.91 0 0 1 2.908-2.91h.001a2.91 2.91 0 0 1 2.909 2.909v4.801m11.813-7.71za2.903 2.903 0 0 1 2.909 2.897v1.903a2.903 2.903 0 0 1-2.896 2.91h-.014a2.903 2.903 0 0 1-2.908-2.898v-1.902a2.903 2.903 0 0 1 2.896-2.91z");
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
