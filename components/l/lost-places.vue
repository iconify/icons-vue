<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ojd_08beb"/><circle class="w24qzsbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lost-places" /></template>
<style>
.ojd_08beb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.603 32.066l11.432 11.432l7.624-7.624m2.264-2.264l1.51-1.51c6.313-6.313 6.313-16.549 0-22.863q0 0 0 0c-6.314-6.314-16.55-6.314-22.865 0q0 0 0 0a16.17 16.17 0 0 0-2.064 20.333");
}

.w24qzsbdg {
  cx: 24.038px;
  cy: 20.631px;
  r: 5.385px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
