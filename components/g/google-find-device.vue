<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfuhwkb3k"/><circle class="k3-d9w7bv"/><circle class="c3f-hsbol"/><path class="gwazo3zpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-find-device" /></template>
<style>
.c3f-hsbol {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gwazo3zpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31 24h14.5c0-11.874-9.626-21.5-21.5-21.5V17");
}

.k3-d9w7bv {
  cx: 24px;
  cy: 24px;
  r: 14.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vfuhwkb3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 24H2.5c0 11.874 9.626 21.5 21.5 21.5V31");
}

</style>
