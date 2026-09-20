<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="p4pbrriiw"/><circle class="i90wfj94a"/><path class="l_5sec_3t"/><path class="ndaqhs3gt"/><circle class="oq4j66bmy"/><path class="p98szcblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digitap" /></template>
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

.i90wfj94a {
  cx: 35.2px;
  cy: 9.875px;
  r: 0.75px;
  fill: currentColor;
}

.l_5sec_3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.2 13.55v7.95m-3.249-7.95v9a3 3 0 0 1-5.122 2.121");
}

.ndaqhs3gt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.951 21.5za3 3 0 0 1-3-3v-1.95a3 3 0 1 1 6 0v1.95a3 3 0 0 1-3 3");
}

.oq4j66bmy {
  cx: 22.7px;
  cy: 9.875px;
  r: 0.75px;
  fill: currentColor;
}

.p4pbrriiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.475 33.75a3 3 0 1 0 6 0V31.8a3 3 0 1 0-6 0m0-3v12m-3-7.05a3 3 0 1 1-6 0V31.8a3 3 0 1 1 6 0m0 4.95V28.8M13.5 24.5h7.95m-3.975 12v-12");
}

.p98szcblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.7 13.55v7.95m-11.2 0v-12h2.7c2.9 0 5.25 2.35 5.25 5.25v1.5c0 2.9-2.35 5.25-5.25 5.25z");
}

</style>
