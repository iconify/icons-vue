<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uhsar3b6z"/><path class="ann4x6kdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:activity-zone" /></template>
<style>
.ann4x6kdn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.405V2.5m0 43v-2.905M42.595 24H45.5m-43 0h2.905m37.19 0l-9.298-9.297l-16.451 16.451m7.503-14.307L7.897 33.298");
}

.uhsar3b6z {
  cx: 24px;
  cy: 24px;
  r: 18.595px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
