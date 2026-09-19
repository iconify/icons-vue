<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uphm7dbrr"/><circle class="i6imtybdf"/><rect transform="rotate(45 24 13.307)" class="w2em2mp_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:futo-keyboard" /></template>
<style>
.i6imtybdf {
  cx: 24px;
  cy: 13.307px;
  r: 8.807px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uphm7dbrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.28 27.406h4.16a1.5 1.5 0 0 1 1.5 1.5v4.16a1.5 1.5 0 0 1-1.5 1.5h-4.16a1.5 1.5 0 0 1-1.5-1.5v-4.16a1.5 1.5 0 0 1 1.5-1.5m5.66-5.366v1.75c0 .83-.67 1.5-1.5 1.5h-4.16c-.83 0-1.5-.67-1.5-1.5v-4.16c0-.63.38-1.16.93-1.38m9.85 9.156h4.16a1.5 1.5 0 0 1 1.5 1.5v4.16a1.5 1.5 0 0 1-1.5 1.5h-4.16a1.5 1.5 0 0 1-1.5-1.5v-4.16a1.5 1.5 0 0 1 1.5-1.5m4.73-9.156c.55.22.93.75.93 1.38v4.16c0 .83-.67 1.5-1.5 1.5h-4.16c-.83 0-1.5-.67-1.5-1.5v-1.75m10.78 5.366H40a1.5 1.5 0 0 1 1.5 1.5v4.16a1.5 1.5 0 0 1-1.5 1.5h-4.16a1.5 1.5 0 0 1-1.5-1.5v-4.16a1.5 1.5 0 0 1 1.5-1.5m0-9.28H40a1.5 1.5 0 0 1 1.5 1.5v4.16a1.5 1.5 0 0 1-1.5 1.5h-4.16a1.5 1.5 0 0 1-1.5-1.5v-4.16a1.5 1.5 0 0 1 1.5-1.5M8 27.406h4.16a1.5 1.5 0 0 1 1.5 1.5v4.16a1.5 1.5 0 0 1-1.5 1.5H8a1.5 1.5 0 0 1-1.5-1.5v-4.16a1.5 1.5 0 0 1 1.5-1.5m0-9.28h4.16a1.5 1.5 0 0 1 1.5 1.5v4.16a1.5 1.5 0 0 1-1.5 1.5H8a1.5 1.5 0 0 1-1.5-1.5v-4.16a1.5 1.5 0 0 1 1.5-1.5m6.668 18.906h18.664a1.5 1.5 0 0 1 1.5 1.5V42a1.5 1.5 0 0 1-1.5 1.5H14.668a1.5 1.5 0 0 1-1.5-1.5v-3.468a1.5 1.5 0 0 1 1.5-1.5");
}

.w2em2mp_w {
  width: 6.243px;
  height: 6.243px;
  x: 20.878px;
  y: 10.186px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.925px;
  ry: 0.925px;
}

</style>
