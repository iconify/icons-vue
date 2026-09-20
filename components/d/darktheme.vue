<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c_ye59ljq"/><rect class="gb_jxebvi"/><path class="sfw44bbqh"/><circle class="t0ixubr4x"/><circle class="fxb1iebph"/><path class="f3z1oeami"/><path class="ht2g3acyx"/><circle class="vk5ih5bfu"/><path class="jft99pbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:darktheme" /></template>
<style>
.c_ye59ljq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.885 17.505c-.422-1.826-3.38-2.077-4.71-1.242c-.624.392-1.351 1.34-1.374 2.58c-.023 1.26.766 2.458.698 3.716c-.18 3.348-2.907 6.276-2.907 9.628c0 2.05.589 4.217 1.778 5.887c1.846 2.59 4.653 4.789 7.73 5.589c2.565.666 5.625.34 7.894-.932M37.07 25.36a2.6 2.6 0 0 1 0 5.2m.45-12.766a2.888 2.888 0 0 1 0 5.777m-.45-12.543a2.792 2.792 0 0 1 0 5.584");
}

.f3z1oeami {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.975 27.309a4.333 4.333 0 1 1-4.901-6.053");
}

.fxb1iebph {
  cx: 23.518px;
  cy: 6.607px;
  r: 0.75px;
  fill: currentColor;
}

.gb_jxebvi {
  width: 21.196px;
  height: 38.719px;
  x: 15.857px;
  y: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.759px;
  ry: 2.759px;
}

.ht2g3acyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.927 27.297a4.14 4.14 0 0 1-4.865-6.007");
}

.jft99pbry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.787 17.775v-.963m-2.042 1.809l-.68-.68m-.166 2.723h-.963m1.809 2.042l-.68.68m2.722.166v.963m2.043-1.809l.68.68m.166-2.722h.963m-1.809-2.043l.68-.68");
}

.sfw44bbqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.169 40.603v-.5l-.5.25zm10.571-.5v.5h.5v-.5zM25.444 6.607h4.38");
}

.t0ixubr4x {
  cx: 26.455px;
  cy: 40.353px;
  r: 0.75px;
  fill: currentColor;
}

.vk5ih5bfu {
  cx: 30.787px;
  cy: 20.663px;
  r: 1.444px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
