<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="b4lds2bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:andotp" /></template>
<style>
.b4lds2bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.48a16.12 16.12 0 0 1 15.83 13.13H8.17A16.11 16.11 0 0 1 24 8.48m0 18.18a2.59 2.59 0 0 1 1.43 4.75l1.43 3.88h-5.72l1.43-3.88A2.59 2.59 0 0 1 24 26.66");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
