<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gjy2tub-u"/><path class="qz51oxbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:attapoll" /></template>
<style>
.gjy2tub-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.04 5.5h17.952l9.485 9.485v27.477h-8.462v-8.736H14.18V42.5H5.523V15.002Z");
}

.qz51oxbgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.411 14.506V25.23H33.59V14.579Z");
}

</style>
