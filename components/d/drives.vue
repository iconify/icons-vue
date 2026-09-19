<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="k260fsbue"/><path class="hyeg_kbij"/><circle class="yo43fuw7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drives" /></template>
<style>
.hyeg_kbij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.375 26.114l6.529 11.278");
}

.k260fsbue {
  cx: 20.616px;
  cy: 17.894px;
  r: 9.502px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yo43fuw7d {
  cx: 24px;
  cy: 23.069px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
