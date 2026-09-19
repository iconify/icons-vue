<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="esh9n_k0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:couchsurfing" /></template>
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

.esh9n_k0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.93 28.92C34.47 28.92 22 28 22 35.51a4.06 4.06 0 0 0 3.78 3.92c1.37 0 4.15-.29 4.15-2.81C30 30 15.63 25.8 15.63 15.44c0-4.92 5.41-6.87 8.68-6.87c3.08 0 8.49 1.95 8.49 8.33c0 6.13-7.33 12.6-16.49 12.6a74 74 0 0 1-13.39-1.27");
}

</style>
