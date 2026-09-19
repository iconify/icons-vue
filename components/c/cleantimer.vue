<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mgjy47b4j"/><path class="oa0suj73v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cleantimer" /></template>
<style>
.mgjy47b4j {
  cx: 24px;
  cy: 25.548px;
  r: 17.952px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oa0suj73v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 25.548V16.88M16.571 4.5H31.43m5.037 8.13l2.482-2.482l2.476 2.476l-2.68 2.68");
}

</style>
