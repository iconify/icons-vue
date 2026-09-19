<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="bu4_yf8hs"/><path class="ax2zd6bok"/><path class="abqbxiizq"/><path class="y21iupp9l"/><path class="gifr8gbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungsri-biz" /></template>
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

.gifr8gbkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.605 9.91c0 6.549 1.054 10.222 5.408 12.458m-11.018 11.43v5.853m2.104-5.853h3.797L26.1 39.65h3.797m-9.434-2.925c.792 0 1.433.655 1.433 1.463s-.641 1.463-1.433 1.463H18.1v-5.853h2.364c.792 0 1.433.655 1.433 1.463s-.641 1.464-1.433 1.464m-.001 0H18.1");
}

.y21iupp9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.395 9.91c0 6.549-1.054 10.222-5.408 12.458M29.615 9.91c0 5.54-.755 9.023-3.625 11.319");
}

</style>
