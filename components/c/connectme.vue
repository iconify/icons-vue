<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="w5idr7pok"/><path class="zgu6xvoih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:connectme" /></template>
<style>
.w5idr7pok {
  width: 30.59px;
  height: 30.59px;
  x: 5.5px;
  y: 11.91px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.zgu6xvoih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.09 27.26h6.41m-6.41-6.79h6.41m-6.41 13.59h6.41M24.2 11.91V5.5m-6.8 6.41V5.5m3.4 30.84V18.06m2.45 2.46l-2.45-2.46l-2.46 2.46m0 13.37l2.46 2.45l2.45-2.45M11.66 27.2h18.28m-2.46 2.46l2.46-2.46l-2.46-2.45m-13.37 0l-2.45 2.45l2.45 2.46");
}

</style>
