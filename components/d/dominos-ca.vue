<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="wzze17bra"/><path class="r9aw0_00d"/><circle class="nk6wddbth"/><circle class="fav2z0x7g"/><circle class="yr-2rb-pk"/><path class="muxdxsmfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dominos-ca" /></template>
<style>
.fav2z0x7g {
  cx: 21.843px;
  cy: 30.508px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.muxdxsmfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.968 40.824h-2.137m-.533 1.661l1.6-4.985l1.6 5m-4.305-1.679v.02c0 .915-.717 1.657-1.6 1.657s-1.6-.742-1.6-1.656v-1.688c0-.915.716-1.656 1.6-1.656h0c.883 0 1.6.741 1.6 1.656v.02");
}

.nk6wddbth {
  cx: 30.543px;
  cy: 17.448px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r9aw0_00d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.813 17.819l12.36 12.359");
}

.wzze17bra {
  width: 35.909px;
  height: 17.47px;
  x: 6.045px;
  y: 15.265px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.9px;
  ry: 0.9px;
}

.yr-2rb-pk {
  cx: 13.113px;
  cy: 30.508px;
  r: 2.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
