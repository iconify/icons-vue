<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cfv6-16my"/><circle class="hgavrfbsq"/><circle class="hgavrfbsq"/><circle class="odgv-00dp"/><circle class="xg24uebnu"/><circle class="yklau2b8f"/><circle class="zabv6dbsu"/><circle class="jbw8m98ee"/><circle class="lro_3bbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ffshare" /></template>
<style>
.cfv6-16my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 35.5v-23M35.5 9h-23M9 12.5v23m3.385 2.423l15.27-4.859m.182-2.751l-8.71-4.645m-.005-3.333l8.742-4.662");
}

.hgavrfbsq {
  cx: 9px;
  cy: 9px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jbw8m98ee {
  cx: 31px;
  cy: 32px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lro_3bbxt {
  cx: 31px;
  cy: 16px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.odgv-00dp {
  cx: 9px;
  cy: 39px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xg24uebnu {
  cx: 39px;
  cy: 39px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yklau2b8f {
  cx: 39px;
  cy: 9px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zabv6dbsu {
  cx: 16px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
