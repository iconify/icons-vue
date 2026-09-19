<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="kn71jqbut"/><path class="wlolk8bft"/><circle class="subdz_blz"/><path class="y6jtp735h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coding-c" /></template>
<style>
.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.kn71jqbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 28.543v5.402a1.8 1.8 0 0 1-3.074 1.273");
}

.subdz_blz {
  cx: 26.765px;
  cy: 26.338px;
  r: 0.75px;
  fill: currentColor;
}

.wlolk8bft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.7 28.543a1.8 1.8 0 0 1 1.8 1.8v1.171a1.8 1.8 0 1 1-3.601 0v-1.17a1.8 1.8 0 0 1 1.8-1.8m-19.86 4.748a1.8 1.8 0 0 1-1.8-1.8v-1.17a1.8 1.8 0 1 1 3.6 0v1.17a1.8 1.8 0 0 1-1.8 1.8");
}

.y6jtp735h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.765 28.543v4.772m-13.901-.996a1.8 1.8 0 0 1-3.364-.894v-1.17a1.8 1.8 0 0 1 3.362-.897m19.863 3.957v-2.971a1.8 1.8 0 1 0-3.601 0m0 2.971v-4.772m-4.71 1.801a1.8 1.8 0 1 0-3.6 0v1.17a1.8 1.8 0 1 0 3.6 0m0 1.801v-7.202m4.338-13.857l-5.543-.001c-.457 0-.878.229-1.1.598l-2.735 4.549a.89.89 0 0 0 .024.956l2.887 4.323a.96.96 0 0 0 .798.413l5.671.008");
}

</style>
