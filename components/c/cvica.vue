<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzal2rsgj"/><circle class="vvha2kb_h"/><path class="vzyt_ob3c"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cvica" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qzal2rsgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.622 25.556v.032a2.563 2.563 0 0 1-2.561 2.565a2.563 2.563 0 0 1-2.56-2.565v-2.614a2.563 2.563 0 0 1 2.56-2.565a2.563 2.563 0 0 1 2.56 2.565v.032m2.218.017v5.13m-.193-7.308l1.353-.484m4.858 2.662l-1.932 5.13l-1.933-5.13");
}

.vvha2kb_h {
  cx: 25.825px;
  cy: 20.651px;
  r: 0.749px;
  fill: currentColor;
}

.vzyt_ob3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.825 23.023v5.13m5.727-.975a1.934 1.934 0 0 1-3.61-.96v-1.26a1.931 1.931 0 0 1 3.609-.964m5.949 2.223c0 1.07-.865 1.936-1.933 1.936a1.934 1.934 0 0 1-1.932-1.936V24.96a1.934 1.934 0 1 1 3.865 0m0 3.193v-5.13");
}

</style>
