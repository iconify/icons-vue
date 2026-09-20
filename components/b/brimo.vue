<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rn6rlzb0s"/><path class="ktpssyngw"/><rect class="lgspslz2g"/><path class="u7mclicsl"/><path class="vz8k8u80s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brimo" /></template>
<style>
.ktpssyngw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.99 25.609V14.377h3.677c2.079 0 3.764 1.69 3.764 3.772s-1.685 3.772-3.764 3.772H23.99m3.677 0l3.677 3.685");
}

.lgspslz2g {
  width: 4.468px;
  height: 5.921px;
  x: 30.032px;
  y: 27.702px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.234px;
  ry: 2.234px;
}

.rn6rlzb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4m-4 8.877v11.232");
}

.u7mclicsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.693 33.623v-3.687a2.234 2.234 0 0 1 4.469 0v3.687");
}

.vz8k8u80s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.162 29.936a2.234 2.234 0 0 1 4.469 0v3.687m-9.498-13.63a2.808 2.808 0 0 1 0 5.616H13.5V14.378h4.633a2.808 2.808 0 0 1 0 5.615m0 0H13.5");
}

</style>
