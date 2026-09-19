<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="trtvg_bam"/><path class="pksn2x4sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:karrot" /></template>
<style>
.pksn2x4sr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5s11.369-4.162 11.369-12.711c0-6.279-5.09-11.369-11.369-11.369s-11.369 5.09-11.369 11.369C12.631 39.339 24 43.5 24 43.5m-.389-25.961c.64-3.616 7.071-3.543 7.071-8.219c0-4.152-2.787-4.82-4.312-4.82c-1.728 0-4.777 1.103-4.574 4.167c-6.156-2.41-11.035 10.396 1.815 8.872");
}

.trtvg_bam {
  cx: 24px;
  cy: 30.789px;
  r: 4.373px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
