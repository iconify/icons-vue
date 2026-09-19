<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nuup2yb0y"/><path class="j1p0x3bqy"/><path class="nlp3_iblt"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bus-tram" /></template>
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

.j1p0x3bqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.113 24.002l7.387.033m-2.333 9.7l-12.684.014c-9.228-.201-13.003-15.05-23.675-15.115l-3.632.01");
}

.nlp3_iblt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.348 14.616l-12.86.032c-9.228.201-13.004 15.055-23.675 15.115l-3.53-.032");
}

.nuup2yb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.113 23.993c-6.714-.49-9.611-4.224-13.284-7.57c-2.971-2.71-6.826-7.25-11.9-7.302l-4.408-.042m29.592 14.923c-6.71.49-9.611 4.229-13.284 7.57c-2.971 2.71-6.826 7.256-11.9 7.303l-4.408.046");
}

</style>
