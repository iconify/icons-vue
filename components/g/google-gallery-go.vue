<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="kxh8acxyx"/><path class="q-g8dkbnz"/><circle class="l-t3ocblt"/><path class="y4eddu-ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-gallery-go" /></template>
<style>
.kxh8acxyx {
  width: 37px;
  height: 30px;
  x: 5.5px;
  y: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.l-t3ocblt {
  cx: 29px;
  cy: 21.601px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q-g8dkbnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 9v23.5H12v-17l23 .101M42.466 32.5H35");
}

.y4eddu-ug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 21.601H5.5M22.9 32.5c0-6.02-4.88-10.9-10.9-10.9");
}

</style>
