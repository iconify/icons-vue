<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyjz7obgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-circle-sharp" /></template>
<style>
.uyjz7obgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12a9 9 0 1 0-9 9v-9zm-6 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
