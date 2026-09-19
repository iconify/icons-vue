<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fs3lqz4go"/><path class="i7oa8rb5f"/><circle class="cgdh5pwhi"/><path class="aod0y3b0s"/><rect class="juzb4ut5d"/><path class="nzh-_hbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:barq" /></template>
<style>
.aod0y3b0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.768 16.767v5.808m-2.293 2.001l-2.587-2.556");
}

.cgdh5pwhi {
  cx: 37.768px;
  cy: 24.576px;
  r: 0.75px;
  fill: currentColor;
}

.fs3lqz4go {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.659 8.159H10.34a4.63 4.63 0 0 0-4.628 4.628v16.5c0 2.542 2.048 4.6 4.584 4.625v5.116a.812.812 0 0 0 1.247.685l9.13-5.797h16.985a4.63 4.63 0 0 0 4.628-4.629v-16.5A4.63 4.63 0 0 0 37.66 8.16");
}

.i7oa8rb5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.236 24.576v-7.809h2.556c1.445 0 2.617 1.174 2.617 2.623s-1.172 2.622-2.617 2.622h-2.556m2.556 0l2.556 2.562m-15.627-3.902a1.952 1.952 0 0 1 0 3.904H9.5v-7.809h3.221a1.952 1.952 0 0 1 0 3.905m0 0H9.5");
}

.juzb4ut5d {
  width: 5.173px;
  height: 7.809px;
  x: 30.302px;
  y: 16.767px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.587px;
  ry: 2.587px;
}

.nzh-_hbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.501 21.989h-3.459m-.857 2.587l2.586-7.809l2.587 7.809");
}

</style>
