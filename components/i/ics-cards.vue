<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k_ynoy9hv"/><path class="sz567lane"/><path class="zpglyoblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ics-cards" /></template>
<style>
.k_ynoy9hv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.337 14.965h7.42V34.37h-7.42zm27.23 12.975a6.487 6.487 0 0 1 0-12.975");
}

.sz567lane {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.08 21.395h-3.621a3.272 3.272 0 1 0 0 6.545h18.13");
}

.zpglyoblx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.85 21.395c3.582 0 6.487 2.962 6.487 6.545s-2.905 6.487-6.488 6.487l-15.39-.057c-5.359 0-9.703-4.344-9.703-9.703s4.344-9.702 9.703-9.702h20.356v6.43H28.907");
}

</style>
