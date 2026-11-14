<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gh6bcz5tt"/><path class="i2p-5-phn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incident-map" /></template>
<style>
.gh6bcz5tt {
  d: path("m2.5 16l6-2.5l7 2.5l6-2.5V19l-6 2.5l-7-2.5l-6 2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2p-5-phn {
  d: path("m5.5 14.75l-2.75-6.5a3 3 0 1 1 5.5 0Zm13 0l-2.75-6.5a3 3 0 1 1 5.5 0Zm-10-1.25V19m7-3v5.5");
}

</style>
