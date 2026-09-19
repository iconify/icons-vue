<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f_sihy8cd"/><path class="t6nrvxbge"/><circle class="ljls8sb3g"/><circle class="u1qoxcb7s"/><path class="ds45usktb"/><circle class="onk38y4ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cittamobi" /></template>
<style>
.ds45usktb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.956 20.472c-1.016 1.481-2.197 2.876-4.468 2.876s-3.452-1.395-4.469-2.876m8.647-1.872s3.515-2.725 3.515-5.332a3.515 3.515 0 0 0-7.03 0c0 2.607 3.515 5.332 3.515 5.332");
}

.f_sihy8cd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.09 24.386v15.127H10.114V13.612a2.07 2.07 0 0 1 2.073-2.073h7.767m-6.331 28.04h3.551v2.885a1.036 1.036 0 0 1-1.036 1.036H14.66a1.036 1.036 0 0 1-1.036-1.036zm17.386 0h3.551v2.885a1.036 1.036 0 0 1-1.036 1.036h-1.48a1.036 1.036 0 0 1-1.035-1.036z");
}

.ljls8sb3g {
  cx: 30.488px;
  cy: 15.897px;
  r: 11.397px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.onk38y4ry {
  cx: 26.31px;
  cy: 13.326px;
  r: 1.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t6nrvxbge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.05 20.472h-6.405v10.109H34.56v-4.039m-20.915 8.57h5.185m10.545 0h5.185M15.464 15.897h3.627");
}

.u1qoxcb7s {
  cx: 34.666px;
  cy: 13.326px;
  r: 1.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
