<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="v792vcb7u"/><path class="m8-n3cfwq"/><path class="kzme-wb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librespeed" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kzme-wb6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.6 29.4c-.2.5-.4.9-.6 1.4M25.9 24L24 12.2L22.2 24a1.8 1.8 0 0 0 .9 1.6a2.12 2.12 0 0 0 1.9 0a1.89 1.89 0 0 0 .9-1.6m-7.7 9.9h.6v.6h-.6zm3.7 0h.6v.6h-.6zm3.6 0h.6v.6h-.6zm3.7 0h.6v.6h-.6z");
}

.m8-n3cfwq {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 2.99 2.99;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 26.3A14.62 14.62 0 1 1 38 28");
}

.v792vcb7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.9 30.5c-.2-.5-.4-.9-.6-1.4");
}

</style>
