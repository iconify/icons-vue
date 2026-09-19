<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gzgbi1rnx"/><circle class="odk-x0bpb"/><circle class="hetzx2j_g"/><circle class="hly8tsv8s"/><path class="wmonp7bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dns-test" /></template>
<style>
.gzgbi1rnx {
  cx: 7.792px;
  cy: 31.316px;
  r: 3.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hetzx2j_g {
  cx: 29.415px;
  cy: 27.476px;
  r: 3.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hly8tsv8s {
  cx: 40.208px;
  cy: 16.684px;
  r: 3.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.odk-x0bpb {
  cx: 20.524px;
  cy: 18.585px;
  r: 3.292px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wmonp7bzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.88 19.011l-6.138 6.138m-8.891-4.237l4.236 4.236M10.12 28.989l8.078-8.078");
}

</style>
