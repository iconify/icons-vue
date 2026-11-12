<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o7vxnob1s"/><path class="h-bumj92r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:import-broken" /></template>
<style>
.h-bumj92r {
  d: path("M12 20C7.58172 20 4 16.4183 4 12M20 12C20 14.5264 18.8289 16.7793 17 18.2454");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o7vxnob1s {
  stroke-linejoin: round;
  d: path("M12 4L12 14M9 11L12 14L15 11");
}

</style>
