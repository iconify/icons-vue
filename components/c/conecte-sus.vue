<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zgdfdvcvt"/><path class="ongm625kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:conecte-sus" /></template>
<style>
.ongm625kf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 24a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 1 6.5 6.5a6.5 6.5 0 0 0-6.5 6.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 0-6.5-6.5a6.5 6.5 0 1 1 6.5-6.5");
}

.zgdfdvcvt {
  cx: 24px;
  cy: 11px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
