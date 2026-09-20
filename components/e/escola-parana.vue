<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s2ed6rypl"/><path class="k3lr1fbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:escola-parana" /></template>
<style>
.k3lr1fbfl {
  fill: currentColor;
  d: path("M29.892 30.192a.75.75 0 0 1-1.5.001a.75.75 0 0 1 1.5 0");
}

.s2ed6rypl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.59 28.302a4.62 4.62 0 0 1-3.995 2.26c-2.54 0-4.598-2.005-4.598-4.478v-2.91c0-2.474 2.058-4.479 4.598-4.479s4.598 2.005 4.598 4.478v1.456h-9.196m6.867 18.867c1.527.067 2.173-.61.497-3.258c-2.544-4.015 3.274-4.19 7.91-6.952c10.866-6.476 11.137-20.662-4.927-28.01c-3.64-1.666-4.798-.64-3.617 2.99c1.294 3.973-1.916 5.484-3.997 6.338l-6.147 2.52C3.715 21.468 2.476 42.5 24.863 43.495z");
}

</style>
