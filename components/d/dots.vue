<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="d1iyv0blr"/><circle class="iduej5bfj"/><circle class="aj5p9tbck"/><circle class="kf6-t6vzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dots" /></template>
<style>
.aj5p9tbck {
  cx: 34.5px;
  cy: 13.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d1iyv0blr {
  cx: 13.5px;
  cy: 13.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iduej5bfj {
  cx: 34.5px;
  cy: 34.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kf6-t6vzx {
  cx: 13.5px;
  cy: 34.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
