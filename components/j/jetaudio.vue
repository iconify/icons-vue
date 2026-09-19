<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ak6bbeffs"/><path class="yzx54spef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jetaudio" /></template>
<style>
.ak6bbeffs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.64 24.47c-2 .47-2.21-1.66.33-3.94c9.86-6.53 21.72-4.76 12.68 6.85l-2.59 2.87c2.21-7.39-4.27-8.54-10.42-5.78");
}

.yzx54spef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.1 26.21q-6.41-1.23-3.03-7.23c4.2-6.48 12.01-11.2 21.86-10.75c10.73 1.6 11.95 7.54 8.35 12.77c-2.64 4.04-8.09 7.18-14.96 10.6q-1.88 2.92-5.13 5.11c-11.21 5.8-17.35-1.48-7.09-10.5");
}

</style>
