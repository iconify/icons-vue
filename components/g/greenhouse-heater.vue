<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoc391bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greenhouse-heater" /></template>
<style>
.uoc391bym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.316 19.5H2.5V9l8-6.5l6.358 5.166m.699.567L18.5 9v.284M2.5 9h13.9m1.8 0h.3m-8 0v10.5M18 13c1.5 1.75 3 3.25 3 5.5a3 3 0 0 1-6 0c0-1.25.5-2 1.25-2.75c0 1 .5 1.75 1 2c0-1.75.25-3.25.75-4.75Z");
}

</style>
