<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cubuh3beh"/><circle class="svids7b8p"/><path class="nv2ibt__f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kinkd" /></template>
<style>
.cubuh3beh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.567 19.97v8.541m.001-1.815l3.866-3.847m-2.636 2.623l3.04 3.026");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nv2ibt__f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.143 22.852v5.659m6.397-.001v-3.523a2.135 2.135 0 0 0-2.135-2.135h0c-1.18 0-2.135.956-2.135 2.135m0 3.524v-5.659m12.572 5.658v-8.54h1.921a3.737 3.737 0 0 1 3.737 3.736v1.068a3.737 3.737 0 0 1-3.737 3.737zM10.5 19.97v8.541m0-2.975l4.591-5.538m0 8.513l-3.517-4.271");
}

.svids7b8p {
  cx: 17.143px;
  cy: 20.237px;
  r: 0.747px;
  fill: currentColor;
}

</style>
