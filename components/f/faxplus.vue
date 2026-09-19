<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gy-405z-o"/><path class="x8pvarbuy"/><path class="ptzkadb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:faxplus" /></template>
<style>
.gy-405z-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 26.478c3.465-8.502 11.23-14.765 14.984-11.518l10.043 8.882c-3.754-3.247-10.717 2.797-14.182 11.3z");
}

.ptzkadb-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.527 23.842c3.064 3.086-5.856 7.201-2.47 9.993");
}

.x8pvarbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.02 20.741c2.047-2.288 4.084-5.098 5.875-7.882L43.5 22.452m0 0c-4.973 8.775-12.481 14.751-16.444 11.382l-7.34-6.108");
}

</style>
