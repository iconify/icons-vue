<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vija-obmz"/><path class="yrhxefbth"/><path class="et4u95bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:efood-delivery" /></template>
<style>
.et4u95bxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.459 31.73a8.8 8.8 0 0 1-4.465 1.2c-4.927 0-8.93-4.003-8.93-8.93s4.003-8.93 8.93-8.93s8.93 4.003 8.93 8.93m-8.93 0H45.5");
}

.vija-obmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.588 41.429a21.43 21.43 0 0 1-12.594 4.065C12.108 45.494 2.5 35.886 2.5 24S12.108 2.506 23.994 2.506S45.488 12.114 45.488 24");
}

.yrhxefbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.524 36.595a15.1 15.1 0 0 1-8.53 2.617c-8.407 0-15.212-6.805-15.212-15.212S15.587 8.788 23.994 8.788S39.206 15.593 39.206 24");
}

</style>
