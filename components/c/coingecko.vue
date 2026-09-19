<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="g0fumnb3q"/><path class="u-trmcbrf"/><circle class="o37n7kdjk"/><circle class="krn4pbaia"/><circle class="jp890ccwp"/><path class="p6shnboih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coingecko" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g0fumnb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.051 37.228c4.519-9.359 1.828-21.471 9.117-23.377s12.056 1.345 15.87 2.467s6.978 1.716 7.682 5.27C40.729 26.693 24.13 35.71 27.664 45.5");
}

.jp890ccwp {
  cx: 34.841px;
  cy: 22.991px;
  r: 0.775px;
  fill: currentColor;
}

.krn4pbaia {
  cx: 21.047px;
  cy: 19.122px;
  r: 1.29px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o37n7kdjk {
  cx: 21.047px;
  cy: 19.122px;
  r: 3.308px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p6shnboih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.375 22.99A18.404 18.404 0 0 0 25.033 5.628");
}

.u-trmcbrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.355 26.972c3.196 2.523 6.496 1.685 13.796-1.373m-8.302-10.062c0-2.273-4.148-4.098-6.719-2.079");
}

</style>
