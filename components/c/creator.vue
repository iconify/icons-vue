<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hdtf_ubuj"/><path class="ahsdj6bdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:creator" /></template>
<style>
.ahsdj6bdl {
  d: path("M10.25 9.15v5.7a.75.75 0 0 0 1.15.65l4.5-2.85a.75.75 0 0 0 0-1.3L11.4 8.5a.75.75 0 0 0-1.15.65");
}

.hdtf_ubuj {
  d: path("m14.16 3.65l3.99 2.3q2.16 1.25 2.16 3.75v4.6q0 2.5-2.16 3.75l-3.99 2.3q-2.16 1.25-4.32 0l-3.99-2.3Q3.69 16.8 3.69 14.3V9.7q0-2.5 2.16-3.75l3.99-2.3q2.16-1.25 4.32 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
