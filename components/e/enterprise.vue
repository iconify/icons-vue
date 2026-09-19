<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtwsn-j-m"/><path class="ud0myqb2x"/><circle class="cpk0fnbgt"/><path class="eqsyg_4hh"/><path class="vyu7q6bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:enterprise" /></template>
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

.eqsyg_4hh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.954 22.811c.876-4.704 6.675-8.01 13.008-7.413s10.843 4.873 10.115 9.59l-.413.015H5.021");
}

.ud0myqb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.264 26.749c-1.445 2.198-4.484 3.59-7.81 3.578c-3.324-.013-6.344-1.428-7.758-3.637");
}

.vyu7q6bbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.02 22.854c.755-3.01 4.336-5.19 8.505-5.181s7.732 2.207 8.462 5.22l-.487.016H5.02");
}

.xtwsn-j-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.526 26.806c-1.613 3.509-6.047 5.866-11.032 5.864s-9.416-2.362-11.025-5.871");
}

</style>
