<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="og6tddc0m"/><path class="kih315n7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:go-escape" /></template>
<style>
.kih315n7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 29.5l39 10m-11.624-2.981l5.862-6.756l1.887 8.743M4.5 8.5c9.53 0 12.925 14.4 10.957 21.745c.974-4.387 4.73-6.903 6.875-7.781");
}

.og6tddc0m {
  cx: 31px;
  cy: 17px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
