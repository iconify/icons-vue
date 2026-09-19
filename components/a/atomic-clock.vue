<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="gznplfboo"/><ellipse transform="rotate(-30 24 24)" class="t0wbdbc0x"/><ellipse transform="rotate(-60 24 24)" class="gznplfboo"/><circle class="uxbxe59_x"/><path class="oal8zz2xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atomic-clock" /></template>
<style>
.gznplfboo {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.024px;
  ry: 21.5px;
}

.oal8zz2xs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.527 6.827l-8.221 14.82m9.072 8.512l-8.069-4.789");
}

.t0wbdbc0x {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.5px;
  ry: 7.024px;
}

.uxbxe59_x {
  cx: 24px;
  cy: 24.001px;
  r: 2.695px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
