<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zrlqhiqtw"/><circle class="ia0fz_bwg"/><circle class="friv-aczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:animepulse" /></template>
<style>
.friv-aczx {
  cx: 38.665px;
  cy: 36.556px;
  r: 3.835px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ia0fz_bwg {
  cx: 9.335px;
  cy: 36.556px;
  r: 3.835px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zrlqhiqtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.805 40.396a3.84 3.84 0 0 1-3.298-5.799l7.964-13.415a3.84 3.84 0 0 1 6.603 3.919L27.11 38.517a3.84 3.84 0 0 1-3.305 1.88ZM16.15 28.698a3.837 3.837 0 0 1-3.297-5.798l7.965-13.416a3.837 3.837 0 0 1 5.26-1.34a3.837 3.837 0 0 1 1.341 5.26l-7.965 13.415a3.84 3.84 0 0 1-3.305 1.879");
}

</style>
