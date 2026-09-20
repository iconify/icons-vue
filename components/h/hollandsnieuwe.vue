<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="j7x6yemcp"/><circle class="j0xu6tunt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hollandsnieuwe" /></template>
<style>
.j0xu6tunt {
  cx: 34.251px;
  cy: 29.663px;
  r: 0.75px;
  fill: currentColor;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.j7x6yemcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.999 15.588v14.266M13 23.97a3.567 3.567 0 1 1 7.133 0v5.884m10.867 0V23.97a3.567 3.567 0 1 0-7.133 0m-.001 5.884v-9.452");
}

</style>
