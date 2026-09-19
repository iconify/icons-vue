<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h556c6bik"/><circle class="meiz9bcpx"/><circle class="bye4gxbbp"/><circle class="oqldv0y3h"/><path class="bqzlp77zu"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cozy-timer" /></template>
<style>
.bqzlp77zu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 24l-8.84-8.84");
}

.bye4gxbbp {
  cx: 39.5px;
  cy: 24px;
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

.h556c6bik {
  cx: 24px;
  cy: 39.5px;
  r: 0.75px;
  fill: currentColor;
}

.meiz9bcpx {
  cx: 8.5px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.oqldv0y3h {
  cx: 24px;
  cy: 8.5px;
  r: 0.75px;
  fill: currentColor;
}

</style>
