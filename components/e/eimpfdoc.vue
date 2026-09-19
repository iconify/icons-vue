<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="njgr39bbk"/><circle class="a5-c7eb1o"/><path class="pnw_75bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eimpfdoc" /></template>
<style>
.a5-c7eb1o {
  cx: 9.383px;
  cy: 11.998px;
  r: 0.75px;
  fill: currentColor;
}

.njgr39bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.496 5.995h27.008a4.5 4.5 0 0 1 4.502 4.499v18.008H28.5v13.504H10.497a4.5 4.5 0 0 1-4.502-4.5v-27.01a4.5 4.5 0 0 1 4.5-4.502z");
}

.pnw_75bsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.383 15.002v6.314m4.08-3.932a2.381 2.381 0 1 1 4.763 0v3.932m-4.763-6.314v6.314m4.763-3.932a2.383 2.383 0 0 1 4.765 0v3.932m3.884-2.383a2.383 2.383 0 0 0 4.764 0v-1.55a2.382 2.382 0 0 0-4.764 0m0-2.381v9.53m9.209-3.216v-7.863c0-.92.745-1.667 1.667-1.667c.822 0 1.334.242 1.686.699m-4.765 2.516h3.335");
}

</style>
