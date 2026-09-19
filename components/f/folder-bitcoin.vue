<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><path class="stakowkxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-bitcoin" /></template>
<style>
.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

.stakowkxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.84 26.5a3.2 3.2 0 0 1 0 6.4h-5.28V20.1h5.28a3.2 3.2 0 0 1 0 6.4m0 0h-5.28m0 6.4h-1.6m1.6-12.8h-1.6m3.2 14.4v-1.6m3.2 1.6v-1.6m-3.2-12.8v-1.6m3.2 1.6v-1.6");
}

</style>
