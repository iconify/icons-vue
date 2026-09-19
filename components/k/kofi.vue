<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z2dunq_vd"/><path class="b32v3w1tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kofi" /></template>
<style>
.b32v3w1tp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.197 25.95l6.45 6.45l6.45-6.45a8.2 8.2 0 0 0 2.402-5.799h0a4.51 4.51 0 0 0-4.212-4.546a4.426 4.426 0 0 0-4.64 4.421a4.426 4.426 0 0 0-4.64-4.42a4.51 4.51 0 0 0-4.212 4.545h0a8.2 8.2 0 0 0 2.402 5.798M32.795 9.853h2.935a7.77 7.77 0 0 1 0 15.54h-2.935");
}

.z2dunq_vd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 9.853h28.295v19.225a9.07 9.07 0 0 1-9.07 9.07H13.57a9.07 9.07 0 0 1-9.07-9.07z");
}

</style>
