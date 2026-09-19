<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5hd_yb2b"/><path class="dzowkbxgr"/><path class="zyrv5obpn"/><path class="v4shm7b5z"/><path class="of4bp-ubr"/><path class="xoqegcc5t"/><path class="nty8webhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cent-mobile" /></template>
<style>
.dzowkbxgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.937 31.528H18.31l-7.281-7.235");
}

.nty8webhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.528 24.649v5.627l-7.235 7.281");
}

.of4bp-ubr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.058 23.937V18.31l7.235-7.281M39.99 24.293l-9.714-9.68H24.65");
}

.v4shm7b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.293 8.596l-9.68 9.714v5.627");
}

.v5hd_yb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.596 24.293l9.714 9.68h5.627");
}

.xoqegcc5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.649 17.058h5.627l7.281 7.235M24.293 39.99l9.68-9.714V24.65");
}

.zyrv5obpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.293 6L11.627 18.666H6v5.627l12.666 12.666v5.627h5.627L36.959 29.92h5.627v-5.627L29.92 11.627V6zm0 12.666l5.627 5.627l-5.627 5.627l-5.627-5.627z");
}

</style>
