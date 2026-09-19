<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p663wibqk"/><path class="n_nc3-bpt"/><circle class="f-5wm485e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:backup" /></template>
<style>
.f-5wm485e {
  cx: 24px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n_nc3-bpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.133 30.127L1.867 24h10.532z");
}

.p663wibqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.073 35.927A16.867 16.867 0 1 0 7.133 24");
}

</style>
