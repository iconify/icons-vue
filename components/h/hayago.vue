<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="s_ttg9brd"/><circle class="iix71gb6e"/><path class="j-bbcdc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hayago" /></template>
<style>
.iix71gb6e {
  cx: 33.75px;
  cy: 33.75px;
  r: 6.882px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j-bbcdc7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.794 24.574h14.912l-4.588 4.014v4.589h1.147v2.294h-1.147v3.44h1.147v2.295h-2.868V43.5h-2.294v-2.294h-2.868v-2.294h1.147V35.47h-1.147v-2.294h1.147v-4.589Zm19.5-1.147h14.912l-4.588-4.015v-4.588h1.147v-2.295h-1.147V9.09h1.147V6.793h-2.868V4.5h-2.294v2.294h-2.868v2.294h1.147v3.441h-1.147v2.295h1.147v4.588Z");
}

.s_ttg9brd {
  cx: 14.25px;
  cy: 14.25px;
  r: 6.882px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
