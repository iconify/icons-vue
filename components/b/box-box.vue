<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="peywjtb9l"/><circle class="ut397xb4w"/><path class="pk1mhirii"/><circle class="si7pic-zj"/><path class="ynt6doblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:box-box" /></template>
<style>
.peywjtb9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.975 22.487c.501-.25.501-.74.501-.987v-.656");
}

.pk1mhirii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.321 13l5.3 8m0-8l-5.3 8m-4.996 0a2.65 2.65 0 0 1-2.65-2.65v-2.7a2.65 2.65 0 1 1 5.3 0v2.7a2.65 2.65 0 0 1-2.65 2.65m-7-4a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3m15.296 9.5l5.3 8m0-8l-5.3 8m-4.996 0a2.65 2.65 0 0 1-2.65-2.65v-2.7a2.65 2.65 0 1 1 5.3 0v2.7a2.65 2.65 0 0 1-2.65 2.65m-7-4a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3");
}

.si7pic-zj {
  cx: 35.225px;
  cy: 34.25px;
  r: 0.75px;
  fill: currentColor;
}

.ut397xb4w {
  cx: 35.225px;
  cy: 20.75px;
  r: 0.75px;
  fill: currentColor;
}

.ynt6doblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.225 26.25v5.95m-21.55 6.4h15.35M13.675 9.4h20.3M9.5 5.5h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4");
}

</style>
