<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u2f6ps77b"/><path class="bc_duhbzn"/><circle class="v3f352h-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:enigmbox" /></template>
<style>
.bc_duhbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.196 30.958a5.545 5.545 0 0 0 7.734-1.29m-7.734-7.734v2.578m7.734-1.288v-2.579m-24.126 9.96a2.08 2.08 0 0 1 .15-1.404a2.1 2.1 0 0 1 .524-.654c.21-.186.442-.348.658-.527a4.9 4.9 0 0 0 1.36-1.785a4.23 4.23 0 0 0 .33-2.213a3.74 3.74 0 0 0-.921-2.03a3.35 3.35 0 0 0-1.95-1.063a3.16 3.16 0 0 0-3.546 2.364");
}

.u2f6ps77b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.41 40.546h1.18l17.728-5.91L43.5 13.364L24.59 18.09h-1.18L4.5 13.364l1.182 21.272ZM4.5 13.364l18.91-5.91h1.18l18.91 5.91");
}

.v3f352h-p {
  cx: 14.014px;
  cy: 32.55px;
  r: 0.75px;
  fill: currentColor;
}

</style>
