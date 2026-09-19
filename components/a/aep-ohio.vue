<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lakkmrbal"/><rect class="j3s9ivbxi"/><path class="fp71-2bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aep-ohio" /></template>
<style>
.fp71-2bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.978 5.5l-1.273 10.584h-6.467l.883-6.864H5.51M32.02 28.5v-9h2.946c1.666 0 3.016 1.353 3.016 3.023s-1.35 3.022-3.016 3.022H32.02M25.205 24h2.934m1.566 4.5h-4.5v-9h4.5m-7.359 6.019h-3.988m-.987 2.981l2.981-9l2.981 9");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lakkmrbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.507 38.741l18.722-.002l.937-6.748l6.365.078L30.107 42.5");
}

</style>
