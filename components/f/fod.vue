<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="lf1sxjz5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fod" /></template>
<style>
.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lf1sxjz5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.359 30.531V17.469h2.868c3.08 0 5.577 2.559 5.577 5.715v1.633c0 3.156-2.497 5.715-5.577 5.715zM10.496 24h4.143m-4.143 6.531V17.469h6.374m6.744 0c2.332 0 4.223 1.937 4.223 4.327v4.408c0 2.39-1.89 4.327-4.223 4.327h0c-2.332 0-4.222-1.937-4.222-4.327v-4.408c0-2.39 1.89-4.327 4.222-4.327");
}

</style>
