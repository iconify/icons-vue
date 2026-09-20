<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vg-zkinst"/><path class="mlmxl8bok"/><path class="ud9jnac7k"/><path class="gq5vtfn6h"/><circle class="fv1p0wbgi"/><circle class="b00h5ezhn"/><circle class="lr5l_fblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:best-connect" /></template>
<style>
.b00h5ezhn {
  cx: 14.879px;
  cy: 24.32px;
  r: 1.686px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fv1p0wbgi {
  cx: 24.219px;
  cy: 35.22px;
  r: 1.296px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gq5vtfn6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.41 30.125a6.318 6.318 0 1 1 8.787-5.823a6.32 6.32 0 0 1-3.934 5.852m-2.384 4.603V26.11m5.916-10.37a8.91 8.91 0 0 1 17.153 3.384a8.91 8.91 0 0 1-6.792 8.652m-2.124-6.224v7.085");
}

.lr5l_fblz {
  cx: 29.035px;
  cy: 19.084px;
  r: 2.475px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mlmxl8bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.758 42.83a7.91 7.91 0 1 1 10.371-7.513a7.91 7.91 0 0 1-5.522 7.535");
}

.ud9jnac7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.758 39.494a4.922 4.922 0 1 1 7.4-4.252a4.93 4.93 0 0 1-2.551 4.317m-2.388 3.778v-6.648M12.41 34.435A10.404 10.404 0 0 1 14.9 13.93h.007a10.404 10.404 0 0 1 10.408 10.4v.003a10.4 10.4 0 0 1-.474 3.109");
}

.vg-zkinst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.567 13.869A14.46 14.46 0 0 1 43.5 19.125a14.46 14.46 0 0 1-11.615 14.177");
}

</style>
