<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-25.08 23.415 20.944)" class="j5xlfs-md"/><path class="vco6qnb6h"/><ellipse transform="rotate(-25.05 23.408 20.93)" class="bxn11thqj"/><path class="sds7-6xkz"/><path class="vt1d1642a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citra" /></template>
<style>
.bxn11thqj {
  cx: 23.41px;
  cy: 20.93px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.91px;
  ry: 1.75px;
}

.j5xlfs-md {
  cx: 23.41px;
  cy: 20.93px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.97px;
  ry: 13.02px;
}

.sds7-6xkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.51 12.51c4.81 10.41.6 22.62-9.4 27.27s-22 0-26.8-10.42");
}

.vco6qnb6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.77 22.16l-15.46 7.2m36.2-16.85l-15.46 7.2m-4.75.63L8.12 16.61m30.58 8.65l-13.18-3.73m-2.84-2.18L17.95 9.11m10.92 23.64l-4.73-10.23m.23-3.69l5.64-12.4M16.82 35.44l5.68-12.5");
}

.vt1d1642a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.82 38.63c-2 0 0-3.19 0-3.19s2.09 3.19 0 3.19");
}

</style>
