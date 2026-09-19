<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jm5x-rdkq"/><circle class="xoeq3mexi"/><circle class="gbho5ac9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:langeasylexis" /></template>
<style>
.gbho5ac9c {
  cx: 23.999px;
  cy: 34.239px;
  r: 9.261px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jm5x-rdkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.099 9.216H29.33m-5.344.436v10.69m1.718-10.734l-6.644 6.798m7.346-2.689l2.755 2.689m-3.739 11.741v3.542l3.805.13m-6.436-3.67v3.671l-3.796.262m1.705 7.937v-6.297h6.887v6.1h-1.18m-5.639-1.965h4.524m-4.455-2.231h4.454m.131-6.102l3.805-.262m-9.866.262l3.254-.132");
}

.xoeq3mexi {
  cx: 24.001px;
  cy: 13.761px;
  r: 9.261px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
