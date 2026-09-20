<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c8s0mublm"/><rect class="gzsf20zfq"/><path class="qsl66lb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icon-pack" /></template>
<style>
.c8s0mublm {
  cx: 34.381px;
  cy: 34.376px;
  r: 8.119px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gzsf20zfq {
  width: 15.224px;
  height: 15.224px;
  x: 26.769px;
  y: 6.459px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.687px;
  ry: 2.687px;
}

.qsl66lb8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.325 27.686l-6.553 11.35A2.03 2.03 0 0 0 7.53 42.08h13.105a2.03 2.03 0 0 0 1.758-3.045L15.84 27.686a2.03 2.03 0 0 0-3.515 0m2.833-21.679za2.24 2.24 0 0 0 2.383.7c.834-.26 1.7.296 1.81 1.163a2.24 2.24 0 0 0 1.626 1.876a1.404 1.404 0 0 1 .894 1.958a2.24 2.24 0 0 0 .353 2.458c.583.65.436 1.67-.306 2.13a2.24 2.24 0 0 0-1.031 2.258a1.404 1.404 0 0 1-1.41 1.626a2.24 2.24 0 0 0-2.088 1.343c-.35.8-1.338 1.09-2.065.606a2.24 2.24 0 0 0-2.483 0a1.404 1.404 0 0 1-2.065-.606a2.24 2.24 0 0 0-2.089-1.343a1.404 1.404 0 0 1-1.409-1.626a2.24 2.24 0 0 0-1.031-2.259a1.404 1.404 0 0 1-.307-2.13a2.24 2.24 0 0 0 .354-2.457a1.404 1.404 0 0 1 .894-1.958A2.24 2.24 0 0 0 8.814 7.87a1.404 1.404 0 0 1 1.81-1.164a2.24 2.24 0 0 0 2.382-.7a1.406 1.406 0 0 1 2.152 0");
}

</style>
