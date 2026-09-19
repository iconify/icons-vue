<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="krc3wu1bp"/><path class="a2xgm7bov"/><path class="us4r5o9py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiovideomanager" /></template>
<style>
.a2xgm7bov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.99 23.43h3.71v3.71h-3.71zm0 12.67h3.71v3.71h-3.71zm0-6.71h3.71v4.45h-3.71zm14.68 1.88l-7.94-4.58a.41.41 0 0 0-.61.35v9.16a.41.41 0 0 0 .61.35L38.67 32a.4.4 0 0 0 0-.73");
}

.krc3wu1bp {
  width: 20.87px;
  height: 20.87px;
  x: 21.63px;
  y: 21.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.03px;
}

.us4r5o9py {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.68 9.32l-11.4-3.19a2 2 0 0 0-2.58 2V27.4a6.2 6.2 0 1 0 3.2 5.43v-.3h0V15.12L28.33 18a2 2 0 0 0 2.58-2v-3.74a3.05 3.05 0 0 0-2.23-2.94");
}

</style>
