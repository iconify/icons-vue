<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibymu9_ki"/><path class="c-hmxwb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:deck" /></template>
<style>
.c-hmxwb7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.64 21.28V17a1 1 0 0 0-1-1H9.36a1 1 0 0 0-1 1v4.27M37.38 16v-4.25a1 1 0 0 0-1-1H11.62a1 1 0 0 0-1 1V16m24.13-5.25V6.48a1 1 0 0 0-1-1h-19.5a1 1 0 0 0-1 1v4.27");
}

.ibymu9_ki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.36 21.28h31.28a2.85 2.85 0 0 1 2.86 2.86v15.52a2.86 2.86 0 0 1-2.86 2.86H8.36a2.86 2.86 0 0 1-2.86-2.86V24.14a2.85 2.85 0 0 1 2.86-2.86");
}

</style>
