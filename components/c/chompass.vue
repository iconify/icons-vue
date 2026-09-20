<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="fj8jalbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chompass" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fj8jalbpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.706V7.953M38.294 24h1.753M24 38.294v1.753M9.706 24H7.953m22.909-6.862l5.216-5.215m-5.216.781l3.003-2.998m1.431 7.432l2.999-3.003m-2.999 3.003a3.135 3.135 0 0 1-4.434-4.434M11.081 36.919l19.781-19.781");
}

</style>
