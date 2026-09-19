<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nk1fgp1ab"/><path class="j39g7le5d"/><circle class="vaed_clnq"/><circle class="sxmoakbfi"/><circle class="ijrc09gku"/><circle class="okrsedb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aliasvault" /></template>
<style>
.ijrc09gku {
  cx: 26.458px;
  cy: 27.666px;
  r: 0.75px;
  fill: currentColor;
}

.j39g7le5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.302 23.684h18.58a3.98 3.98 0 0 1 3.981 3.982h0a3.98 3.98 0 0 1-3.981 3.981h-18.58a3.98 3.98 0 0 1-3.981-3.981h0a3.98 3.98 0 0 1 3.98-3.982");
}

.nk1fgp1ab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.638 37.62h19.907c5.497 0 9.954-4.456 9.955-9.953c0-2.51-.948-4.929-2.655-6.77c-.414-6.216-5.79-10.92-12.006-10.506a11.28 11.28 0 0 0-9.229 5.994a8.626 8.626 0 0 0-13.27 7.3a8.626 8.626 0 0 0 7.298 13.934Z");
}

.okrsedb6x {
  cx: 32.218px;
  cy: 27.666px;
  r: 0.75px;
  fill: currentColor;
}

.sxmoakbfi {
  cx: 20.712px;
  cy: 27.666px;
  r: 0.75px;
  fill: currentColor;
}

.vaed_clnq {
  cx: 14.965px;
  cy: 27.666px;
  r: 0.75px;
  fill: currentColor;
}

</style>
