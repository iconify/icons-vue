<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gva0igavn"/><circle class="aboxku6xe"/><path class="sleykbbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:afet-acil" /></template>
<style>
.aboxku6xe {
  cx: 28.111px;
  cy: 27.37px;
  r: 0.75px;
  fill: currentColor;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gva0igavn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.814 23.5v-8h1.8c1.9 0 3.5 1.6 3.5 3.5v1c0 1.9-1.6 3.5-3.5 3.5zm-11.249-4h2.6m-2.6 4v-8h4m-7.179 5.3h-3.6m-.9 2.7l2.7-8l2.7 8m10.492-2.7h-3.6m-.9 2.7l2.7-8l2.7 8");
}

.sleykbbnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.111 29.77v5.4m2.293-8v7c0 .6.4 1 1 1h.3m-5.674-1c-.3.6-1 1-1.7 1h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c.7 0 1.4.4 1.7 1m-5.734 2.3c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m0 3.3v-5.4");
}

</style>
