<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qyizzd1ae"/><path class="ds_-22b8d"/><path class="nc027abkt"/><path class="hamu_tclc"/><path class="volg5zd6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hoosegow" /></template>
<style>
.ds_-22b8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.22 28.005l-1.889-.725l8.645-4.581l8.542 4.71l-1.89.544");
}

.hamu_tclc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.028 13.898l-.13 4.141l7.896 5.514m-15.971.259l8.076-5.772m0 0l.077 4.659");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nc027abkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.868 25.948l-.146-2.473l2.071.078l-1.915-4.452l-5.85-5.203l-6.238 5.643l-1.967 4.27l2.588-.258l-.502 2.361");
}

.qyizzd1ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.003 42.5l-.001-17.756l6.626 3.21L32.684 42.5m-8.682-17.756l-6.782 3.261l-2.152 14.405M5.5 38.82l10.933-5.545m14.981-.027l11.086 5.63");
}

.volg5zd6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.081 34.459c-1.68-1.703-3.36-3.406-4.269-6.5s-1.047-7.581.653-11.17c1.7-3.59 5.237-6.281 8.982-7.506s7.696-.984 11.018.742s6.014 4.935 7.29 8.507c1.278 3.572 1.14 7.506.185 10.193s-2.725 4.127-4.496 5.567");
}

</style>
