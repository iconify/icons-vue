<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c5cjgzbpf"/><path class="x09loybdy"/><path class="my64q2aeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-close-broken" /></template>
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

.my64q2aeo {
  d: path("M9.73223 9.73223L11.5 11.5M11.5 11.5L13.2678 13.2678M11.5 11.5L9.73223 13.2678M11.5 11.5L13.2678 9.73223");
}

.x09loybdy {
  d: path("M6.75 3.27093C8.14732 2.46262 9.76964 2 11.5 2C16.7467 2 21 6.25329 21 11.5C21 16.7467 16.7467 21 11.5 21C6.25329 21 2 16.7467 2 11.5C2 9.76964 2.46262 8.14732 3.27093 6.75");
}

</style>
