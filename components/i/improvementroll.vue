<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hy_hf-l-e"/><path class="prf5x8ker"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:improvementroll" /></template>
<style>
.hy_hf-l-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.252 31.262A12.973 12.973 0 0 1 24 11.027m10.756 5.719A12.973 12.973 0 0 1 24 36.97");
}

.prf5x8ker {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.906l6.703-6.703L24 4.5h0zm-.001 12.188l-6.703 6.703l6.703 6.703z");
}

</style>
