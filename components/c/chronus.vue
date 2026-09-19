<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ow_g2ru2j"/><path class="zzjqesrzr"/><path class="n7cb5nxuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chronus" /></template>
<style>
.n7cb5nxuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.471 15.04a8.962 8.962 0 0 0-7.742 13.472m18.732-11.325a4.6 4.6 0 0 0-3.36 1.194");
}

.ow_g2ru2j {
  cx: 23.471px;
  cy: 24px;
  r: 3.162px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zzjqesrzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.471 20.838V4.5m0 39V32.984m2.728-7.394l14.132 8.236m-19.59-8.235l-14.13 8.235m11.602 4.416h10.516m5.362-8.051a6.532 6.532 0 1 0 .766-13.017q-.2 0-.396.011v.002a11.84 11.84 0 0 0-10.99-6.944a13.76 13.76 0 0 0-11.887 20.685");
}

</style>
