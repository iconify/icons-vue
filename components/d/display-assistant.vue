<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qtgsqktdi"/><circle class="xm8sqtbrk"/><circle class="qxkqzns9v"/><circle class="kafy2-ton"/><path class="uvifvu5mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:display-assistant" /></template>
<style>
.kafy2-ton {
  cx: 30px;
  cy: 31px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qtgsqktdi {
  cx: 24px;
  cy: 24px;
  r: 14.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qxkqzns9v {
  cx: 18px;
  cy: 17px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uvifvu5mz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 24h-4m43 0h-4M24 6.5v-4m0 43v-4M11.626 11.626L8.798 8.798m30.405 30.405l-2.828-2.828m-.001-24.749l2.828-2.828M8.797 39.203l2.829-2.828M16 31h12m-7.5-14H32m-16 7h6m4 0h6");
}

.xm8sqtbrk {
  cx: 24px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
