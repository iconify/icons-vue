<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="j3vz_7ucu"/><path class="oytnb02oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flypgs" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3vz_7ucu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.658 30.992v-.79L12.424 5.883h6.236l14.312 17.482s1.827 2.058 2.971 2.79c1.098.702 2.373 1.103 3.624 1.466c1.768.513 5.432.993 5.432.993m-16.287 4.522l-14.656-2.834h-3.161l6.156 3.02l6.197 1.472z");
}

.oytnb02oe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.388 41.573l-.256.178l-19.348-5.878l-.68-3.014m28.389-2.356l-25.08.835");
}

</style>
