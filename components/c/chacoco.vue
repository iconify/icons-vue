<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5cj_kvrf"/><rect class="scgbe1hyy"/><path class="eheenn0sp"/><rect class="e0_l7iben"/><path class="w05xy4b5j"/><path class="yt2ujrv6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chacoco" /></template>
<style>
.e0_l7iben {
  width: 3.977px;
  height: 6.002px;
  x: 40.523px;
  y: 23.095px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.988px;
  ry: 1.988px;
}

.eheenn0sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.683 27.085v.024c0 1.098-.89 1.989-1.988 1.989h0a1.99 1.99 0 0 1-1.988-1.989v-2.025c0-1.098.89-1.989 1.988-1.989h0c1.098 0 1.988.89 1.988 1.989v.024");
}

.p5cj_kvrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.004 23.095v6.003m3.977-6.003v6.003m-3.977-3.013h3.977m-5.954 1v.024c0 1.098-.89 1.989-1.988 1.989h0a1.99 1.99 0 0 1-1.988-1.989v-2.025c0-1.098.89-1.989 1.988-1.989h0c1.098 0 1.988.89 1.988 1.989v.024m17.057 1.977v.024c0 1.098-.89 1.989-1.988 1.989h0a1.99 1.99 0 0 1-1.988-1.989v-2.025c0-1.098.89-1.989 1.988-1.989h0c1.098 0 1.988.89 1.988 1.989v.024");
}

.scgbe1hyy {
  width: 3.977px;
  height: 6.002px;
  x: 28.876px;
  y: 23.095px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.988px;
  ry: 1.988px;
}

.w05xy4b5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.105 27.109h-2.66m-.658 1.989l1.988-6.003l1.988 6.003");
}

.yt2ujrv6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.246 20.998c-1.414-7.686-8.135-13.514-16.23-13.514C10.895 7.484 3.5 14.88 3.5 24s7.395 16.516 16.516 16.516c6.623 0 12.32-3.908 14.952-9.535");
}

</style>
