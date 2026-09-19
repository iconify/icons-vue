<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="pe1u62_hq"/><path class="gqvn0cz_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-photoshop-camera" /></template>
<style>
.gqvn0cz_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.146 10.99A13.9 13.9 0 0 0 24 10c-7.732 0-14 6.268-14 14s6.268 14 14 14s14-6.268 14-14c0-1.819-.358-3.552-.989-5.146");
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

.pe1u62_hq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.913 30.5v-13h4.256c2.406 0 4.357 1.955 4.357 4.366s-1.95 4.366-4.357 4.366h-4.256m10.623 3.541c.594.499 1.234.727 2.673.727h.73a2.15 2.15 0 0 0 2.148-2.153h0a2.15 2.15 0 0 0-2.149-2.153H28.48a2.15 2.15 0 0 1-2.148-2.153h0a2.15 2.15 0 0 1 2.148-2.153h.73c1.438 0 2.079.228 2.672.726");
}

</style>
