<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l9e5azbzm"/><path class="z8fbb045i"/><path class="s5d2ctx3y"/><path class="pvs4qdrki"/><path class="ascozysly"/><path class="l6gobcbas"/><path class="jjf660bwg"/><ellipse class="dhm6i4b8f"/><path class="hcbjukn_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dinomail" /></template>
<style>
.ascozysly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.648 42.192l5.99.177l1.234-2.064l1.15.08l3.585-2.25l-.717-1.611l2.694-2.686l-1.13-3.631l2.902-1.49l-1.493-4.344l2.942-4.22l-4.186-4.115l.207-5.826l-4.461.007l-3.154-5.718l-5.262 1.826l-2.998-1.456l-4.017 5.496l-3.493-.387l1.01 3.81l-2.014 1.541l.293 2.273");
}

.dhm6i4b8f {
  cx: 21.681px;
  cy: 33.865px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.917px;
  ry: 1.065px;
}

.hcbjukn_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M15.705 34.315c-.48-.584-1.201-.754-3.39-.9");
}

.jjf660bwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M12.845 36.524a4.83 4.83 0 0 1-2.385-1.166m11.716 1.632c-1.641 0-3.304-.49-3.343-3.575c-.05-3.86 5.277-3.784 5.747-1.45c.816 3.967-2.528 4.454-1.793.652");
}

.l6gobcbas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.34 19.355a4.86 4.86 0 0 1-3.543-.906c-.634-.547-.117 2.665 2.047 4.462m-4.02 16.871s-.416-1.007.617-1.041");
}

.l9e5azbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.524 14.59S20.46 7.852 11.73 17.605m0-.001s-2.305.2-3.383-.738c-.643-.558-.223 3.5 1.975 5.418");
}

.pvs4qdrki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.558 41.824s1.473 3.514 8.09.367c0 0 3.844-.044 7.96-4.26");
}

.s5d2ctx3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.624 38.848s-3.798-.788 1.674 4.063a7.65 7.65 0 0 1 5.535-3.103");
}

.z8fbb045i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.342 19.98s-3.59 7.05.973 13.436m.001-.001s.13 2.923-1.856 1.943c0 0 .293 2.809 1.165 3.49");
}

</style>
