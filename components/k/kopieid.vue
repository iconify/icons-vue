<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqo9pjw0y"/><path class="kn3t3ub7n"/><path class="fvblabqye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kopieid" /></template>
<style>
.fvblabqye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.055 28.43a9.47 9.47 0 0 0-4.516-2.372a3.168 3.168 0 1 0-3.975 0A9.47 9.47 0 0 0 8.05 28.43");
}

.kn3t3ub7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.051 17.5h13v13h-13zm18.074 3.796h8.252m-8.281 5.467l12.197.028");
}

.kqo9pjw0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.5v-25a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2v25a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2");
}

</style>
