<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="happl2g3b"/><circle class="txth7xkhr"/><path class="lai4t_3gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitdefender-vpn" /></template>
<style>
.happl2g3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.118 9.328l7.928 3.13v7.598c0 2.4 1.6 15.596-15.046 23.444C7.354 35.652 8.954 22.455 8.954 20.056v-7.598l7.928-3.13");
}

.lai4t_3gw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.67 12.17a7.67 7.67 0 1 0-10.688 7.05v8.985l2.575 2.574l-2.575 2.575v2.357L24 37.75l3.018-2.039V19.22a7.67 7.67 0 0 0 4.651-7.051");
}

.txth7xkhr {
  cx: 24px;
  cy: 8.49px;
  r: 1.981px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
