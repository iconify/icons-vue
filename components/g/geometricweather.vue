<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xiwgnjb5n"/><path class="vm21pabmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geometricweather" /></template>
<style>
.vm21pabmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.61 42.38L36.85 34l.16-.22l7.49-4.33L40.19 22v-.28l2.24-8.35L34 11.15l-.18-.15l-4.33-7.5L22 7.81l-.28.05l-8.33-2.24L11.15 14l-.16.22l-7.49 4.29L7.81 26c0 .09 0 .19.05.28l-2.24 8.33L14 36.85l.22.16l4.33 7.49L26 40.19h.28Z");
}

.xiwgnjb5n {
  cx: 24px;
  cy: 24px;
  r: 16.32px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
