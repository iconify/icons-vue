<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o2piwwbno"/><path class="xouwyzbiw"/><path class="lcclbrb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ancestry" /></template>
<style>
.lcclbrb4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.99 24.043c.616-6.178-4.505-17.057-20.24-15.89c1.496 1.56-1.53 11.926 12.563 16.024");
}

.o2piwwbno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.857 7.98v16.037L43.5 40.02m-.643-16.003c-6.725 0-18.044.32-18.044.32m0 .001c-6.697-7.733-15.13-5.729-20.313-.51c3.586 5.665 16.558 7.53 20.313.51");
}

.xouwyzbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.99 24.043c.616 6.178-4.505 17.058-20.24 15.89c.903-1.233-.13-10.693 12.843-15.762");
}

</style>
