<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fvkubhbyt"/><path class="lpe6nibpe"/><circle class="d55jto4db"/><circle class="zqmv81blp"/><path class="yu77rubyn"/><path class="l9y5d5bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cardinal-quest-2" /></template>
<style>
.d55jto4db {
  cx: 24.022px;
  cy: 14.586px;
  r: 0.75px;
  fill: currentColor;
}

.fvkubhbyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.341 12.195h29.996M18.769 4.5h13.14v7.695h-13.14zm0 7.695v5.288h13.14v-5.288m0 5.288V40.15h3.403v3.35H15.367v-3.35h3.402V17.483m0 16.175h13.14");
}

.l9y5d5bfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.341 6.106h3.045v3.045h-3.045z");
}

.lpe6nibpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.769 20.362l7.539 7.015l5.601-6.125m-7.708 9.724h2.408m-1.459 2.682V43.5m-6.381-27.536l-8.428 6.806h8.428m-8.794 5.915v4.712h5.182v-4.712h3.612m-8.794-.314l3.402-5.601m-.732 10.627v4.606h6.124m13.14-22.039l8.428 6.806h-8.428m8.795 5.915v4.712h-5.183v-4.712h-3.612m8.795-.314l-3.403-5.601m.733 10.627v4.606h-6.125");
}

.yu77rubyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.296 9.15h3.045v3.045H7.296z");
}

.zqmv81blp {
  cx: 29.012px;
  cy: 14.586px;
  r: 0.75px;
  fill: currentColor;
}

</style>
