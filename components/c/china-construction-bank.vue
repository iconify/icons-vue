<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aiaho5pmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:china-construction-bank" /></template>
<style>
.aiaho5pmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.997 8.251l12.498 12.294l-3.435 3.381l-8.11-7.981l-10.128 9.969l10.13 9.968l8.108-7.981l8.677.053A18.125 18.125 0 1 1 23.997 8.25m3.745-2.189l11.79 11.494l2.913-2.868l-7.634-7.763c-3.527-3.587-8.507-4.782-11.971-1.505c.373-.106 3.786-.446 4.902.642");
}

</style>
