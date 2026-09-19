<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="gkx1dyl4g"/><path class="q3f0vluoq"/></g><path class="bvq1ayb5q"/><g class="y9tr6bcfx"><path class="q1aercbxk"/><path class="zy65i50xx"/></g><path class="yflj4jfgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lien-viet-24h" /></template>
<style>
.bvq1ayb5q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M17.395 20.831L4.5 20.854m26.105-.022l12.895.023");
}

.gkx1dyl4g {
  d: path("M17.395 20.831A19.5 19.5 0 0 1 24 27.098m0 .001a19.5 19.5 0 0 1 6.604-6.267m.001-.001A19.5 19.5 0 0 1 24 14.564");
}

.q1aercbxk {
  d: path("M43.5 20.855a19.5 19.5 0 0 1-39 0");
}

.q3f0vluoq {
  d: path("M23.999 14.565a19.5 19.5 0 0 1-6.604 6.267");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yflj4jfgf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M17.395 20.831h13.21");
}

.zy65i50xx {
  d: path("M37.21 20.855a13.21 13.21 0 1 1-26.42 0m0 0a13.21 13.21 0 1 1 26.42 0");
}

</style>
