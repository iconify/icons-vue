<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="toobnu3yi"/><circle class="v2rmnkb2g"/><path class="hv83xtb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:klarna" /></template>
<style>
.hv83xtb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.591 26.03A22.86 22.86 0 0 0 31.49 7.914h-8.162a18.05 18.05 0 0 1-11.06 16.507l12.797 15.665h9.007Z");
}

.toobnu3yi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 7.914h7.769v32.172H4.5z");
}

.v2rmnkb2g {
  cx: 39.584px;
  cy: 36.17px;
  r: 3.916px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
