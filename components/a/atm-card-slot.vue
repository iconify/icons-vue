<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn94xccbv"/><path class="es0ngpbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-card-slot" /></template>
<style>
.es0ngpbos {
  d: path("M8.75 11.5h3.5v3h-3.5Z");
}

.hn94xccbv {
  d: path("M2.5 4h19v4.5h-19ZM6 8.5v10A2.5 2.5 0 0 0 8.5 21h7a2.5 2.5 0 0 0 2.5-2.5v-10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
