<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cvcgena1q"/><rect class="ipn6ekfhs"/><circle class="p5-hbvh5d"/><circle class="gxd9m4frf"/><rect class="wbad3hvfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:composer" /></template>
<style>
.cvcgena1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.97 36.55c-3.18 0-5.65-2.58-5.76-5.76V17.21c0-3.18 2.58-5.76 5.76-5.76s5.83 2.58 5.82 5.76v13.54a5.817 5.817 0 0 1-5.82 5.81Z");
}

.gxd9m4frf {
  cx: 10.26px;
  cy: 17.21px;
  r: 5.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ipn6ekfhs {
  width: 11.52px;
  height: 11.52px;
  x: 4.5px;
  y: 25.03px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.3px;
  ry: 2.3px;
}

.p5-hbvh5d {
  cx: 37.74px;
  cy: 30.79px;
  r: 5.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wbad3hvfe {
  width: 11.52px;
  height: 11.52px;
  x: 31.98px;
  y: 11.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.3px;
  ry: 2.3px;
}

</style>
