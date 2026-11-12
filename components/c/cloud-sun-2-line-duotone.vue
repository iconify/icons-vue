<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gw83f_1-z"/><path class="s7e920tsu"/><path class="ipyoirb8q"/><path class="ugs80abio"/><path class="biyqeebyg"/><path class="us27dkrpi"/><path class="ruy-b-vne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-sun-2-line-duotone" /></template>
<style>
.biyqeebyg {
  d: path("M11.3887 3.61108L11.1726 3.82714");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gw83f_1-z {
  d: path("M8.66667 14.2426C8.20528 13.9374 7.68058 13.7184 7.11616 13.6089C6.8475 13.5567 6.56983 13.5294 6.28571 13.5294C3.91878 13.5294 2 15.4256 2 17.7647C2 20.1038 3.91878 22 6.28571 22H16.2857C19.4416 22 22 19.4717 22 16.3529C22 13.8811 20.393 11.7802 18.1551 11.015C17.5693 10.8147 16.9404 10.7059 16.2857 10.7059C15.6178 10.7059 14.9767 10.8191 14.381 11.0272M7.11616 13.6089C6.88706 12.9978 6.7619 12.3369 6.7619 11.6471C6.7619 8.52827 9.32028 6 12.4762 6C15.4159 6 17.8371 8.19371 18.1551 11.015");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipyoirb8q {
  d: path("M7.5 2V2.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ruy-b-vne {
  d: path("M3.82812 3.82697L3.61206 3.6109");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.s7e920tsu {
  d: path("M11 6.19621C10.8463 5.94113 10.661 5.70725 10.4495 5.5C10.3105 5.36376 10.1601 5.23903 10 5.12734C9.43308 4.73191 8.74362 4.5 8 4.5C7.25638 4.5 6.56692 4.73191 6 5.12734C5.83988 5.23903 5.68954 5.36376 5.55051 5.5C4.90223 6.13526 4.5 7.02066 4.5 8C4.5 9.3962 5.31753 10.6015 6.5 11.1632M5.55051 5.5C5.55051 5.5 5.55051 5.5 5.55051 5.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ugs80abio {
  d: path("M2.5 7.5L2 7.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.us27dkrpi {
  d: path("M3.82812 11.173L3.61206 11.3891");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
