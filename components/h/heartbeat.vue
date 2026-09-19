<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e4s4rsb_q"/><path class="h37ulnbmd"/><path class="g09npzbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:heartbeat" /></template>
<style>
.e4s4rsb_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 41.824l16.23-19.05A10.13 10.13 0 1 0 24 10.694");
}

.g09npzbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 41.824L7.77 22.774A10.13 10.13 0 1 1 24 10.693");
}

.h37ulnbmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14 21.114h5l3-6l4 12l3-6h5");
}

</style>
