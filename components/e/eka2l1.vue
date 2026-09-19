<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zf2ihdymk"/><circle class="cli-spbbj"/><path class="pyayq__-q"/><path class="eax3p-d4q"/><path class="qlxvjebfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eka2l1" /></template>
<style>
.cli-spbbj {
  cx: 38.99px;
  cy: 37.8px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eax3p-d4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.67 20.79c2.49 0 5-2.49 5-6.47S25.78 6.8 20 6.8s-6.84 3.8-6.84 7.2m.46 5.69a6.21 6.21 0 0 0-4.93 6.09c0 3.13 3.5 5 3.5 5");
}

.pyayq__-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.21 26.44l18.78 8.11m-1 6.65H19.14m-8.96-23.7a7.33 7.33 0 0 0-5.68 7.29a7.5 7.5 0 0 0 1.65 4.7m35.57 6.29c2.07-1.72 2.83-10.28-.48-13.55a18.18 18.18 0 0 0-13.82-5.69");
}

.qlxvjebfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.61 19.79c-3.34 0-5.1-3.25-5.1-3.25c.71-1.17 3.16-2.53 4.68-2.81l.63 1.58a7.17 7.17 0 0 0 4.32.91s-.27 3.57-4.53 3.57m1.2-7.23v-1.13m3.16 1.13v-1.13M6.15 29.49l7.79 9.6m23.51-8.17c1.44.56 6 1.9 6-.42");
}

.zf2ihdymk {
  cx: 19.14px;
  cy: 33.67px;
  r: 7.52px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
