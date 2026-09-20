<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lj5rgj0nn"/><path class="aj6ez8_ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:honor-health" /></template>
<style>
.aj6ez8_ib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.858 11.853C35.855 6.988 27.412 6.804 24 12.165c-3.412-5.36-11.854-5.176-15.858-.312C-1.953 24.117 19.84 39.826 24 39.826s25.953-15.71 15.858-27.973");
}

.lj5rgj0nn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.221 16.053c-.64 0-1.254.255-1.707.707l-6.546 6.551l-3.14-3.216a2.413 2.413 0 1 0-3.452 3.374l4.844 4.962a2.413 2.413 0 0 0 3.433.02l8.274-8.277a2.415 2.415 0 0 0-1.705-4.12Z");
}

</style>
