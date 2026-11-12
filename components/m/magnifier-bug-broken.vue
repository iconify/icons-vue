<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="swrlsub8n"/><path class="x09loybdy"/><path class="c5cjgzbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-bug-broken" /></template>
<style>
.c5cjgzbpf {
  d: path("M18.2168 18.2178L21.9994 22.0004");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.swrlsub8n {
  d: path("M14.5 10.5V12.5C14.5 14.1569 13.1569 15.5 11.5 15.5M14.5 10.5C14.5 8.84315 13.1569 7.5 11.5 7.5C9.84315 7.5 8.5 8.84315 8.5 10.5M14.5 10.5H11.5M8.5 11.5V12.5C8.5 14.1569 9.84315 15.5 11.5 15.5M8.5 11.5V10.5M8.5 11.5H7M8.5 10.5H11.5M11.5 15.5V10.5M14.5715 11.5H16M14.5 14L15.5 14.5M8.5 14L7.5 14.5M14.5 9L15.5 8.5M8.5 9L7.5 8.5");
}

.x09loybdy {
  d: path("M6.75 3.27093C8.14732 2.46262 9.76964 2 11.5 2C16.7467 2 21 6.25329 21 11.5C21 16.7467 16.7467 21 11.5 21C6.25329 21 2 16.7467 2 11.5C2 9.76964 2.46262 8.14732 3.27093 6.75");
}

</style>
