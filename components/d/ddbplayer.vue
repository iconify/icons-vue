<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="zeop1-bjl"/><path class="tt01-ac3m"/><path class="ij-4kb--d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ddbplayer" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ij-4kb--d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.347 37.5h-2.736l2.736-2.846v-7.808");
}

.tt01-ac3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.347 10.5h-2.736l2.736 2.846m0 10.654h-2.736l2.736 2.846m0-2.846V13.346");
}

.zeop1-bjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.347 24h11.307c3.72 0 6.735-3.022 6.735-6.75h0c0-3.728-3.015-6.75-6.735-6.75H13.61l2.736 2.846M16.347 24h11.307c3.72 0 6.735 3.022 6.735 6.75h0c0 3.728-3.015 6.75-6.735 6.75H16.347");
}

</style>
