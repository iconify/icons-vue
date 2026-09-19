<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="rontpgnkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:authenticate" /></template>
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

.rontpgnkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.17 3.42L15.49 18.83a4.3 4.3 0 0 0-1.58 5.87h0a4.3 4.3 0 0 0 5.88 1.58l7.9-4.56a4.29 4.29 0 0 1 5.87 1.58h0A4.29 4.29 0 0 1 32 29.17L5.31 44.58");
}

</style>
