<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9dl54n7g"/><circle class="rewj60bbc"/><path class="qcn_py8dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dictionary" /></template>
<style>
.q9dl54n7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.73 4.5H10.4a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h2.33m0-39v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

.qcn_py8dv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.723 27.142l-6.052 6.052");
}

.rewj60bbc {
  cx: 28.195px;
  cy: 22.671px;
  r: 6.329px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
