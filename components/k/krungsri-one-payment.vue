<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="bu4_yf8hs"/><path class="ax2zd6bok"/><path class="abqbxiizq"/><path class="y21iupp9l"/><path class="jme15lbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-one-payment" /></template>
<style>
.abqbxiizq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.385 9.91c0 5.54.755 9.023 3.625 11.319");
}

.ax2zd6bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.343c-6.302 0-11.411 5.11-11.411 11.412S17.698 31.166 24 31.166s11.411-5.11 11.411-11.411S30.302 8.343 24 8.343");
}

.bu4_yf8hs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.078 28.699C22.61 23.676 24 17.196 24.016 8.343c.016 8.853 1.405 15.333 6.937 20.356");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.jme15lbdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.605 9.91c0 6.549 1.054 10.222 5.408 12.458M22.575 39.646v-5.843l3.79 5.843v-5.843m2.3 2.922h1.864m.996 2.921h-2.86v-5.843h2.86m-13.15 0c1.05 0 1.895.864 1.895 1.936v1.971c0 1.073-.845 1.936-1.895 1.936h0c-1.05 0-1.895-.863-1.895-1.936v-1.97c0-1.072.846-1.936 1.895-1.936");
}

.y21iupp9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.395 9.91c0 6.549-1.054 10.222-5.408 12.458M29.615 9.91c0 5.54-.755 9.023-3.625 11.319");
}

</style>
