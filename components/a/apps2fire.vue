<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="s5cbacb7i"/><path class="la0fvjztp"/><circle class="ce1w7kb4e"/><path class="oo1c-ybuw"/><path class="d8mrafbjm"/><circle class="iu8ktwbun"/><circle class="lioofebld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apps2fire" /></template>
<style>
.ce1w7kb4e {
  cx: 21.931px;
  cy: 30.878px;
  r: 0.7px;
  fill: currentColor;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d8mrafbjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M28.727 10.593L30.5 8.821m-11.227 1.772L17.5 8.821");
}

.iu8ktwbun {
  cx: 21.144px;
  cy: 14.158px;
  r: 0.75px;
  fill: currentColor;
}

.la0fvjztp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.808 22.82c1.76 1.4 7 3.54 12.49 3.54a17 17 0 0 0 10.16-3.08");
}

.lioofebld {
  cx: 26.867px;
  cy: 14.158px;
  r: 0.75px;
  fill: currentColor;
}

.oo1c-ybuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.931 33.328v5.299m-4.131.001v-6.6a1.4 1.4 0 0 1 1.4-1.4a1.63 1.63 0 0 1 1.42.59m-3.999 2.11h2.8m4.655 2a2 2 0 0 1 2-2m-2 0v5.299m7.044-.999a2 2 0 0 1-1.74 1a2 2 0 0 1-2-2v-1.29a2 2 0 0 1 2-2a2 2 0 0 1 2 2v.65h-4m-9.983-20.784a6.604 6.604 0 0 1 13.207 0v3.116a.69.69 0 0 1-.68.688h-11.83a.69.69 0 0 1-.696-.688Z");
}

.s5cbacb7i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.288 22.3c1.11-.45 3.09-1.05 3.69-.33s-.17 2.48-.92 3.8");
}

</style>
