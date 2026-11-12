<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u04hmj8af"/><path class="sww6cebxb"/><path class="bwsf8zpll"/><path class="sr5bgubyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-2-linear" /></template>
<style>
.bwsf8zpll {
  d: path("M9 11L8 17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sr5bgubyr {
  d: path("M9 6V5C9 3.34315 10.3431 2 12 2C13.6569 2 15 3.34315 15 5V6");
}

.sww6cebxb {
  d: path("M15 11L16 17");
}

.u04hmj8af {
  d: path("M3.74132 20.5545C3.74132 20.5545 3.74132 20.5545 3.74132 20.5545C4.94094 22 7.17365 22 11.6391 22H12.3602C16.8257 22 19.0584 22 20.258 20.5545M3.74132 20.5545C2.5417 19.1091 2.95316 16.9146 3.77608 12.5257C4.3613 9.40452 4.65392 7.84393 5.76481 6.92196M20.258 20.5545C20.258 20.5545 20.258 20.5545 20.258 20.5545C21.4576 19.1091 21.0461 16.9146 20.2232 12.5257C19.638 9.40452 19.3454 7.84393 18.2345 6.92196M18.2345 6.92196C18.2345 6.92196 18.2345 6.92196 18.2345 6.92196C17.1236 6 15.5358 6 12.3602 6H11.6391C8.4635 6 6.87571 6 5.76481 6.92196C5.76481 6.92196 5.76482 6.92196 5.76481 6.92196");
}

</style>
