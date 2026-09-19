<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="av9ta433h"/><circle class="uwdp17aat"/><circle class="mt9hnjich"/><circle class="lidmnccjg"/><path class="yjm1qhb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kinoteatr" /></template>
<style>
.av9ta433h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.066 20.64v9.198m-6.178 0V20.64m6.178 0l-6.178 9.198M39 23.712a3.09 3.09 0 0 0-3.255-3.085c-1.67.088-2.923 1.587-2.923 3.26v2.862a3.09 3.09 0 0 0 3.089 3.089h0A3.09 3.09 0 0 0 39 26.748zM9 20.609v9.225m1.193-4.612l3.406-4.582m-3.406 4.582l3.406 4.626m-3.406-4.626H9m15.355-4.582v9.198m6.178-9.198v9.198m-6.178-4.616h6.178");
}

.lidmnccjg {
  cx: 33.486px;
  cy: 18.816px;
  r: 0.664px;
  fill: currentColor;
}

.mt9hnjich {
  cx: 38.336px;
  cy: 18.816px;
  r: 0.664px;
  fill: currentColor;
}

.uwdp17aat {
  cx: 35.911px;
  cy: 18.816px;
  r: 0.664px;
  fill: currentColor;
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
