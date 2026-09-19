<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="qcn3g7bih"/><ellipse class="o22lonb0a"/><path class="k6-ukdsaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bewakoof" /></template>
<style>
.k6-ukdsaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.017 15.187c4.832-1.175 6.693-.053 9.957 3.106");
}

.o22lonb0a {
  cx: 34.061px;
  cy: 26.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.439px;
  ry: 7.249px;
}

.qcn3g7bih {
  cx: 13.939px;
  cy: 26.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.439px;
  ry: 7.249px;
}

</style>
