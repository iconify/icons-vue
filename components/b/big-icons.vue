<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grsbnzbwy"/><path class="aullvbbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:big-icons" /></template>
<style>
.aullvbbbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.165 16.688v4.875H8.84v-4.875m12.99 0v4.875h-4.326v-4.875m21.657 0v4.875h-4.326v-4.875m-4.339 0v4.875h-4.327v-4.875");
}

.grsbnzbwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16.688h39v14.625h-39z");
}

</style>
