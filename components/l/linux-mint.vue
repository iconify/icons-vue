<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l4pz3ib_x"/><path class="k0doo7b5g"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linux-mint" /></template>
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

.k0doo7b5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.31 28.18v-8.847c0-2.062 1.543-3.91 3.601-4.017a3.807 3.807 0 0 1 4.012 3.801v9.59a5.916 5.916 0 0 1-5.917 5.917H18.995a5.916 5.916 0 0 1-5.916-5.916V13.376");
}

.l4pz3ib_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.31 19.117a3.807 3.807 0 1 0-7.614 0v9.063");
}

</style>
