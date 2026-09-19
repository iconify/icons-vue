<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ve01k5brg"/><path class="w_qam98jt"/><path class="qtkizybvr"/><circle class="u1f0bfb0z"/><path class="p5ljg-bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bird-alone" /></template>
<style>
.p5ljg-bdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.37 11.502s2.256-1.97 4.028-2.526c2.253-.706 6.144-1.57 8.329 1.16c.65.813.341 1.897.341 2.936c0 1.2.201 2.77 0 3.277c-1.434 3.618-6.417 6.076-6.417 6.076");
}

.qtkizybvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.363 8.48C.189 22.833 5.673 29.405 6.56 30.3c.05.05.126.018.14-.05c.235-1.223 1.312-3.288 3.03-5.594m9.261-8.744c-3.85 2.48-7.075 5.808-9.261 8.744m0 0c.132 1.287 2.571 2.104 3.956 2.104c2.757 0 4.243-.137 6.306-.137c.844-.107 1.425-.226 1.548-.304");
}

.u1f0bfb0z {
  cx: 23.977px;
  cy: 12.177px;
  r: 1.771px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ve01k5brg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.743 16.77c-2.58.768-2.649 5.16-2.58 6.879c.475 11.808-7.453 11.895-13.472 8.885");
}

.w_qam98jt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.323 27.713C39.555 17.943 32.845 5.5 20.39 5.5c-2.863 0-6.276.978-6.758 1.495c-.355.38-.402.87-.355 1.24c.276 2.203 5.72 6.371 7.934 11.218c.435.954.335 1.558.335 2.606V42.5");
}

</style>
