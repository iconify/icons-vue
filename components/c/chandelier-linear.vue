<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wwa_f4b-v"/><path class="deabmibaa"/><path class="xw-fhxbcm"/><path class="z45gdf-iy"/><path class="kx7ftwqzz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chandelier-linear" /></template>
<style>
.deabmibaa {
  d: path("M12 4V16.5C12 18.433 13.567 20 15.5 20C17.433 20 19 18.433 19 16.5V16.4444");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx7ftwqzz {
  d: path("M5 16C6.65685 16 8 14.6569 8 13V10.8571C8 10.3838 7.61624 10 7.14286 10H2.85714C2.38376 10 2 10.3838 2 10.8571V13C2 14.6569 3.34315 16 5 16Z");
}

.wwa_f4b-v {
  d: path("M9 4H15");
}

.xw-fhxbcm {
  d: path("M19 16C17.3431 16 16 14.6569 16 13V11.2C16 10.5373 16.5373 10 17.2 10H20.8C21.4627 10 22 10.5373 22 11.2V13C22 14.6569 20.6569 16 19 16Z");
}

.z45gdf-iy {
  d: path("M12 4V16.5C12 18.433 10.433 20 8.5 20C6.567 20 5 18.433 5 16.5V16.4444");
}

</style>
