<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vta870bve"/><path class="lt7j86jjt"/><path class="cz_7jaczd"/><path class="l6md27rub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-linear" /></template>
<style>
.cz_7jaczd {
  stroke-linejoin: round;
  d: path("M5 19H19");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6md27rub {
  stroke-linejoin: round;
  d: path("M2 16H22");
}

.lt7j86jjt {
  stroke-linejoin: round;
  d: path("M8 22H16");
}

.vta870bve {
  d: path("M20.6486 16C21.4916 15.0161 22 13.7432 22 12.3529C22 9.88113 20.393 7.78024 18.1551 7.01498C17.5693 6.81468 16.9404 6.70588 16.2857 6.70588C15.6178 6.70588 14.9767 6.81911 14.381 7.02721M7.11616 9.60887C6.8475 9.55673 6.56983 9.52941 6.28571 9.52941C3.91878 9.52941 2 11.4256 2 13.7647C2 14.5852 2.2361 15.3512 2.64482 16M7.11616 9.60887C6.88706 8.9978 6.7619 8.33687 6.7619 7.64706C6.7619 4.52827 9.32028 2 12.4762 2C15.4159 2 17.8371 4.19371 18.1551 7.01498M7.11616 9.60887C7.68058 9.71839 8.20528 9.9374 8.66667 10.2426");
}

</style>
