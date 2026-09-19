<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="prjuukbsa"/><circle class="th5s-bcbf"/><path class="nsykrpbwj"/><path class="l9dzxovrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-music" /></template>
<style>
.l9dzxovrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.262 18.445v-5.907a3.795 3.795 0 0 1 3.795-3.795h14.648a3.795 3.795 0 0 1 3.795 3.795v5.907");
}

.nsykrpbwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.262 31.876v-14.54a1.9 1.9 0 0 1 1.898-1.897h18.443a1.897 1.897 0 0 1 1.897 1.898v14.539");
}

.prjuukbsa {
  cx: 12.881px;
  cy: 31.876px;
  r: 7.381px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.th5s-bcbf {
  cx: 35.119px;
  cy: 31.876px;
  r: 7.381px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
