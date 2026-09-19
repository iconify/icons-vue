<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vgo61abte"/><circle class="z4zem-blj"/><path class="ntcjuyqjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:firewall" /></template>
<style>
.ntcjuyqjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.5 28.6l9.2-9.2");
}

.vgo61abte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.1 14.5v-8a2 2 0 0 0-2-2H14.9a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h18.2a2 2 0 0 0 2-2v-8m-22.2-24h22.2m-22.2 29h22.2");
}

.z4zem-blj {
  cx: 35.1px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
