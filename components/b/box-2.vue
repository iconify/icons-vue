<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xldl_9ben"/><path class="iocgifb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:box-2" /></template>
<style>
.iocgifb1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.5 18.188a3.312 3.312 0 1 0 6.625 0v-3.376a3.312 3.312 0 1 0-6.625 0zM19 16.5a2.5 2.5 0 1 1 0 5h-4.125v-10H19a2.5 2.5 0 1 1 0 5m0 0h-4.125m11.625 15h6.625");
}

.xldl_9ben {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-23.625 21l6.625 10m0-10l-6.625 10");
}

</style>
