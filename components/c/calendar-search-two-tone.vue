<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ezwva2b8c"/><path class="y2jrcdbfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-search-two-tone" /></template>
<style>
.ezwva2b8c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 4L18 4C20.2091 4 22 5.7909 22 8L22 11C22 11.5523 21.5523 12 21 12L15 12C13.3431 12 12 13.3431 12 15L12 21C12 21.5523 11.5523 22 11 22L6 22C3.7909 22 2 20.2091 2 18L2 8C2 5.7909 3.7909 4 6 4Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y2jrcdbfr {
  d: path("M11 21H6C4.34315 21 3 19.6569 3 18V8C3 6.34315 4.34315 5 6 5H18C19.6569 5 21 6.34315 21 8V11M7 11H17M8 3V7M16 3V7M20 17.5C20 18.8807 18.8807 20 17.5 20C16.1193 20 15 18.8807 15 17.5C15 16.1193 16.1193 15 17.5 15C18.8807 15 20 16.1193 20 17.5ZM19.5 19.5L21 21");
}

</style>
