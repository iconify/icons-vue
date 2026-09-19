<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tpufq7bru"/><path class="romfa263c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fotmob" /></template>
<style>
.romfa263c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.991 35.989v5.297M43.5 6.714H19.991v16.959m7.786 5.006L6.971 39.039M4.5 31.462l21.197-6.135");
}

.tpufq7bru {
  cx: 31.746px;
  cy: 23.887px;
  r: 6.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
