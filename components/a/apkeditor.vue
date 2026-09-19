<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xano--bdb"/><path class="n3tel_btl"/><path class="paxx8s_7m"/><path class="hglijdilu"/><circle class="letk1yu6t"/><path class="g8s7cdcrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apkeditor" /></template>
<style>
.g8s7cdcrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 23.68v-2.164m6.686 20.87L24 28.457l-6.686 13.929");
}

.hglijdilu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.865 38.486V43.5h1.114a3.134 3.134 0 0 0 2.786-2.786V20.657");
}

.letk1yu6t {
  cx: 24px;
  cy: 26.229px;
  r: 2.229px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n3tel_btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.261 17.894v-2.229a9.717 9.717 0 0 1 9.762-9.716h0a9.717 9.717 0 0 1 9.716 9.716v2.229M15.643 4.5l2.452 3.009M32.424 4.5l-2.518 3.009");
}

.paxx8s_7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.236 15.086V35.7a3.134 3.134 0 0 0 2.786 2.786h22.843V23.443h1.114a3.134 3.134 0 0 0 2.786-2.786a3.134 3.134 0 0 0-2.786-2.786H12.022a3.134 3.134 0 0 1-2.786-2.785a3.134 3.134 0 0 1 2.786-2.786h2.73");
}

.xano--bdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.078 14.34a1.37 1.37 0 1 1 1.36-1.316a1.37 1.37 0 0 1-1.36 1.315m7.934.001a1.37 1.37 0 1 1 1.359-1.316a1.37 1.37 0 0 1-1.36 1.315");
}

</style>
