<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r194_mahp"/><path class="u1_8zmb8a"/><path class="z7rxm9u2c"/><path class="jshl38fbo"/><path class="wkgct6bwb"/><path class="n7fnvel1r"/><circle class="pyyllxbjp"/><path class="qkzsvybhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abfallinfoapp" /></template>
<style>
.jshl38fbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.378 9.531l-3.15 22.083");
}

.n7fnvel1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.974 10.88c-.08-1.311.06-1.76 1.565-2.391c1.507-.633 2.29-.436 2.399.417m8.68 6.456c-.502-1.23.387-1.657 1.317-2.173s2.073-.722 2.4.174m-10.781-2.746C21.028 11.73 23 12.272 23 12.272l5.325-2.385");
}

.pyyllxbjp {
  cx: 32.357px;
  cy: 36.396px;
  r: 0.75px;
  fill: currentColor;
}

.qkzsvybhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.684 4.5l12.968 3.498");
}

.r194_mahp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.348 12.052l14.948-6.517L37.375 9.09l-15.478 7.87z");
}

.u1_8zmb8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.264 13.155l3.462 25.86L24 43.5l4.822-3.168");
}

.wkgct6bwb {
  fill: none;
  stroke: currentColor;
  d: path("M33.229 31.768c-2.813-.14-6.106 6.814-3.505 8.574s4.666-1.82 5.054-2.76c.363-.884 1.853-5.645-1.55-5.814Z");
}

.z7rxm9u2c {
  fill: none;
  stroke: currentColor;
  d: path("m23.755 16.116l.358 27.08");
}

</style>
