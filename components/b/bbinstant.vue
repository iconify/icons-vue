<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="l7sq1abap"/><g class="y9tr6bcfx"><path class="xlbwaliok"/><path class="vuqfgymrk"/></g><circle class="iafdt2i8p"/><path class="meu2jn8tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbinstant" /></template>
<style>
.iafdt2i8p {
  cx: 10.226px;
  cy: 32.954px;
  r: 0.625px;
  fill: currentColor;
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

.l7sq1abap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 31h37");
}

.meu2jn8tu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.226 35.129v4.705m19.226-1.776a1.78 1.78 0 0 1-1.785 1.776h0a1.78 1.78 0 0 1-1.785-1.776v-1.154c0-.98.8-1.775 1.785-1.775h0a1.78 1.78 0 0 1 1.785 1.775m0 2.93v-4.705m-13.616 4.705v-2.93a1.78 1.78 0 0 0-1.785-1.775h0a1.78 1.78 0 0 0-1.784 1.775m0 2.93v-4.705m22.683 4.705v-2.93a1.78 1.78 0 0 0-1.785-1.775h0a1.78 1.78 0 0 0-1.785 1.775m.001 2.93v-4.705m-13.493 4.308c.326.272.678.397 1.468.397h.4c.652 0 1.18-.527 1.18-1.177h0c0-.65-.528-1.176-1.18-1.176h-.8c-.652 0-1.18-.526-1.18-1.176h0c0-.65.528-1.176 1.18-1.176h.4c.79 0 1.142.125 1.468.397m2.591-1.862v5.282c0 .49.4.888.892.888h.268m-2.097-4.705h1.874m12.886-1.465v5.282c0 .49.4.888.893.888h.267m-2.097-4.705h1.874");
}

.vuqfgymrk {
  d: path("M25.907 16.024c2.518-1.056 5.364-.357 6.976 1.712c1.611 2.069 1.6 5.008-.03 7.204s-4.482 3.118-6.992 2.259");
}

.xlbwaliok {
  d: path("M15.257 8.882V27.86m11.769-6.349c.008 3.385-2.605 6.14-5.843 6.16s-5.883-2.7-5.914-6.085c-.032-3.385 2.562-6.158 5.8-6.203s5.901 2.656 5.956 6.04M22.246 8.86v5.492");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
