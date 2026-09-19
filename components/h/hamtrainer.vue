<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clkwj00vq"/><g class="y9tr6bcfx"><path class="jiab2bnmq"/><circle class="tdejlb8kn"/><path class="bs-knwbxw"/><path class="fy2goabzi"/><path class="n04ivxb0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hamtrainer" /></template>
<style>
.bs-knwbxw {
  d: path("M31.877 4.5c9.14 5.075 10.443 20.083-.38 26.452m-15.664 0c-9.148-5.075-10.45-20.083.38-26.452");
}

.clkwj00vq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.754 33.446V43.5m6.734-10.054V43.5m-6.734-5.048h6.734m11.046 4.974v-9.98l4.974 9.988l4.965-9.98v9.98");
}

.fy2goabzi {
  d: path("M28.753 9.782c5.687 4.177 6.032 11.374 0 15.897m-9.692-.052c-5.687-4.177-6.032-11.375 0-15.897");
}

.jiab2bnmq {
  d: path("m20.64 43.474l3.496-10.442m3.34 10.468l-3.34-10.468m2.218 6.973h-4.549m2.288-6.559l-.07-13.317");
}

.n04ivxb0e {
  d: path("M30.332 7.106c7.198 4.108 8.501 15.76-.276 21.11M17.43 28.13c-7.198-4.108-8.5-15.76.276-21.11");
}

.tdejlb8kn {
  cx: 24.023px;
  cy: 17.514px;
  r: 2.46px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
