<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="rju8ysfdi"/><circle class="y87211knh"/><circle class="ps0ge-28y"/><path class="mjb7ug8qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gamelauncher" /></template>
<style>
.mjb7ug8qg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.443 6.557L28.757 19.243m12.686 0L28.757 6.557");
}

.ps0ge-28y {
  cx: 35.1px;
  cy: 35.1px;
  r: 7.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rju8ysfdi {
  cx: 12.9px;
  cy: 12.9px;
  r: 7.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y87211knh {
  cx: 12.9px;
  cy: 35.1px;
  r: 7.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
