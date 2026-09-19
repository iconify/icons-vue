<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly65dgb_m"/><path class="qv-ohbp3k"/><circle class="ek_7q6btb"/><path class="rw2gfcc6n"/><path class="h2h11obxq"/><path class="rfyz24b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:busbahnbim" /></template>
<style>
.ek_7q6btb {
  cx: 10px;
  cy: 28.75px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h2h11obxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.689 20.75H25l-.75 4.5h5.653m-3.359-5.5h6.097M29 29.25h9.5m-6-9.5a7 7 0 0 1 2 .5a9 9 0 0 1 1 .5c.929.535 1.787 1.2 2.5 2c.8.9 1.404 1.953 2 3c.185.324.37.65.5 1c.18.484.25 1.026.091 1.517c-.08.246-.216.475-.405.65s-.43.3-.686.333c-.166.022-.333.007-.5 0a6 6 0 0 0-.5 0");
}

.ly65dgb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4zm-4 11.75h13.375");
}

.qv-ohbp3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.875 17.25q.545 2.24 1 4.5c.2.994.388 1.992.5 3a20.4 20.4 0 0 1 0 4.5m0 0h-8.439");
}

.rfyz24b0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.518 22.25H32.5l-.5 3h7.714");
}

.rw2gfcc6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.063 29.25H5.5m13.648-10H5.5m11.5 0l-1.125 7m4.5 0h-4.5m.5-3.5H10m9.115-4.5H23m-2.625 11H29m1-1a1 1 0 0 1-1 1m1-1a42 42 0 0 1 0-1c.004-.333.012-.667 0-1a8.5 8.5 0 0 0-2.078-5.244A8.5 8.5 0 0 0 23 18.25");
}

</style>
