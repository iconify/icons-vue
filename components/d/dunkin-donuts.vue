<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sx-5s7odk"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dunkin-donuts" /></template>
<style>
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

.sx-5s7odk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.987 37.5V25.903L21.67 37.5V25.903M26.444 10.5v7.756a3.842 3.842 0 0 0 7.683 0V10.5m-20.14 11.597V10.5h2.61a5.074 5.074 0 0 1 5.073 5.074v1.45a5.074 5.074 0 0 1-5.074 5.073zm13.182 3.806V37.5m0-4.039l6.233-7.519m0 11.558l-4.775-5.799m7.038-5.929l-.511 2.463");
}

</style>
