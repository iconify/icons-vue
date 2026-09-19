<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rnhj4mbpn"/><path class="r_ngn1g-w"/><circle class="nv8g_39sg"/><path class="wxln5ti9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exiferaser" /></template>
<style>
.nv8g_39sg {
  cx: 29.299px;
  cy: 23.477px;
  r: 3.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r_ngn1g-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.024 36.565l7.036-7.035l4.122 4.123l6.905-6.904l6.38 6.38M9.993 22.477v-7.639a7.133 7.133 0 0 1 14.267 0v3.583");
}

.rnhj4mbpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.024 15.82H43.5v24.476H19.024z");
}

.wxln5ti9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.487 23.011l-5.494-4.06l-5.493 4.06v16.56h10.987z");
}

</style>
