<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="nmz64wdpb"/><rect class="n7idynb-d"/></g><g class="y9tr6bcfx"><path class="iquj7dboo"/><path class="fv4ar5b7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kuro-reader" /></template>
<style>
.fv4ar5b7g {
  d: path("M24 24.64c-6.106-4.35-13.5-.107-13.5-.107V42.5s7.394-4.399 13.5-.065zm0 17.795c6.106-4.334 13.5.065 13.5.065V24.533s-7.394-4.243-13.5.108z");
}

.iquj7dboo {
  d: path("M24 24.64c-6.106-4.35-13.5-.107-13.5-.107V42.5s7.394-4.399 13.5-.065z");
}

.n7idynb-d {
  width: 27px;
  height: 13.901px;
  x: 10.5px;
  y: 5.5px;
  rx: 0.998px;
  ry: 0.998px;
}

.nmz64wdpb {
  d: path("M14.57 8.742v7.167m3.864-.008l-2.945-3.576l2.945-3.552m2.019 2.39v2.95a1.788 1.788 0 1 0 3.576 0v-2.95m0 2.819v1.792m2.019-2.823c0-.987.8-1.788 1.788-1.788m-1.788 0v4.738m5.594 0zc-.987 0-1.788-.8-1.788-1.788v-1.162a1.788 1.788 0 1 1 3.576 0v1.162c0 .988-.8 1.788-1.788 1.788");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
