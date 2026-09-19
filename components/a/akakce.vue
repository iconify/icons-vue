<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="dg1rauc1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:akakce" /></template>
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

.dg1rauc1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 23.684a3.298 3.298 0 0 1 5.63-2.332l3.212 3.212h0l8.53-8.53a3.298 3.298 0 0 1 5.628 2.333h0c0 .875-.348 1.714-.966 2.333L22.983 32.25a2.32 2.32 0 0 1-3.283 0l-6.234-6.233a3.3 3.3 0 0 1-.966-2.333");
}

</style>
