<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kguly92mf"/><circle class="n0mzehzbh"/><path class="hwshtacpt"/><circle class="cpk0fnbgt"/><path class="e_h3bsb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:india-map-quiz" /></template>
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

.e_h3bsb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.29 14.5H4.71m38.58 19H4.71");
}

.hwshtacpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 22.303v-5.799m1.2 6.296l4.1-4.1M25.697 24h5.799M25.2 25.2l4.1 4.1M24 25.697v5.799M22.8 25.2l-4.1 4.1m3.603-5.3h-5.799m6.296-1.2l-4.1-4.1m5.739 3.661l1.501-5.601m-.471 6.392l5.022-2.9m-4.852 4.187l5.601 1.501m-6.392-.471l2.9 5.022m-4.187-4.852L22.06 31.24m.471-6.392l-5.022 2.9m4.852-4.187L16.76 22.06m6.392.471l-2.9-5.022m4.596 5.022l2.9-5.022m-2.109 6.052l5.601-1.501m-5.771 2.788l5.022 2.9m-6.052-2.109l1.501 5.601m-2.788-5.771l-2.9 5.022m2.109-6.052L16.76 25.94m5.771-2.788l-5.022-2.9m6.052 2.109L22.06 16.76");
}

.kguly92mf {
  cx: 24px;
  cy: 24px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n0mzehzbh {
  cx: 24px;
  cy: 24px;
  r: 1.697px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
