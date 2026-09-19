<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d1n_y_tdd"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:led-scroller" /></template>
<style>
.d1n_y_tdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 18.597v10.806h5.403M20.456 24h3.523m1.88 5.403h-5.403V18.597h5.403m2.481 10.806V18.597h2.432a4.73 4.73 0 0 1 4.728 4.728v1.35a4.73 4.73 0 0 1-4.728 4.728z");
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

</style>
