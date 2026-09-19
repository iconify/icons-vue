<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ze419wy8d"/><circle class="nxhbm_b9g"/><circle class="jzcu_dbyf"/><path class="e8tci0rjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anton" /></template>
<style>
.e8tci0rjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M33.568 30.155a10.935 10.935 0 0 1-19.122.203");
}

.jzcu_dbyf {
  cx: 30.27px;
  cy: 12.864px;
  r: 0.75px;
  fill: currentColor;
}

.nxhbm_b9g {
  cx: 17.98px;
  cy: 12.864px;
  r: 0.75px;
  fill: currentColor;
}

.ze419wy8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.457 20.667a2.76 2.76 0 1 0-5.52 0v2.811a2.76 2.76 0 0 0 5.52 0zm-13.21-2.76h5.52m-2.76 8.331v-8.331m-10.951 8.331v-8.331l5.52 8.331v-8.331m19.404 8.331v-8.331l5.52 8.331v-8.331M9.105 23.479h-3.69M4.5 26.238l2.76-8.331l2.76 8.331");
}

</style>
