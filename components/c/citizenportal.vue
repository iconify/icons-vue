<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="puey75bqz"/><path class="i7rz8nb5t"/><path class="qfef9v6wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citizenportal" /></template>
<style>
.i7rz8nb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.389 20.983A16.822 16.822 0 1 1 22.8 6.96q.487 0 .967.027");
}

.puey75bqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.178 2.5A21.723 21.723 0 1 1 3.479 33.714");
}

.qfef9v6wy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.367 13.983l1.19 3.663h3.852l-3.116 2.264l1.19 3.664l-3.116-2.264l-3.116 2.264l1.19-3.664l-3.116-2.264h3.852z");
}

</style>
