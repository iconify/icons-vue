<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eba3fmo5v"/><path class="nfe0bqezc"/><circle class="o3azcttch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-lock-closed" /></template>
<style>
.eba3fmo5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.652 21.587v-5.228c0-5.331-4.321-9.653-9.652-9.653s-9.652 4.322-9.652 9.653v5.228");
}

.nfe0bqezc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.522 21.587h28.956v19.706H9.522z");
}

.o3azcttch {
  cx: 24px;
  cy: 31.44px;
  r: 3.016px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
