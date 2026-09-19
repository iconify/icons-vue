<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="b1w5hzzmd"/><circle class="p015yvbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cbs" /></template>
<style>
.b1w5hzzmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.15c-9.052 0-16.981 4.736-21.5 11.85C7.019 31.114 14.948 35.85 24 35.85S40.981 31.113 45.5 24C40.981 16.886 33.052 12.15 24 12.15");
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

.p015yvbcc {
  cx: 24px;
  cy: 24px;
  r: 11.849px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
