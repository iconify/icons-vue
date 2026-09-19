<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wbt7vtfel"/><path class="uj0h6mmju"/><circle class="hs7eydbmx"/><circle class="cpk0fnbgt"/><path class="s6wucrx0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:localch" /></template>
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

.hs7eydbmx {
  cx: 27.284px;
  cy: 18.024px;
  r: 11.023px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s6wucrx0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.048 41.16c18.877.448 22.722-.41 33.64-11.308");
}

.uj0h6mmju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.673 10.01c.925 3.05.832 8.664.617 12.529");
}

.wbt7vtfel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.541 15.742c4.992-.555 9.43-.309 12.572.739");
}

</style>
