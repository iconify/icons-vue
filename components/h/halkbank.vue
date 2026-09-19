<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b1z40abgn"/><path class="sv1qxwb_e"/><path class="c9hc8yb5x"/><path class="sz1-2bcag"/><path class="hv4wk_sho"/><path class="mojs-1bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:halkbank" /></template>
<style>
.b1z40abgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.65 14.895v18.21m2.248-21.359v24.508m2.496-28.07v31.633M14.76 4.5v39m0-19.459h18.48M17.216 8.405v13.313h13.52V8.364m9.614 6.531v18.21m-2.248-21.359v24.508m-2.496-28.07v31.633M33.24 4.5v39");
}

.c9hc8yb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.875 15.2v1.934h4.18v-1.94");
}

.hv4wk_sho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.875 32.938v-1.933h4.18v1.939");
}

.mojs-1bop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.49 36.334v-7.599h8.983v7.622");
}

.sv1qxwb_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.216 8.405v13.313h13.52V8.364");
}

.sz1-2bcag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.49 11.805v7.598h8.983v-7.622M17.216 39.734V26.42h13.52v13.354");
}

</style>
