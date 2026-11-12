<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="v_tnx689j"/><path class="d67ta4_sa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-off-linear" /></template>
<style>
.d67ta4_sa {
  d: path("M6.7863 17.2137C4.3595 15.2553 2 12.8629 2 9.13699C2 4.2741 7.5002 0.825395 12 5.50059C14.6535 2.74369 17.6549 2.81169 19.6711 4.32889");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.v_tnx689j {
  d: path("M21.2633 6.19177C21.7307 7.05607 21.9995 8.06197 21.9995 9.13697C21.9995 14 17.9801 16.5914 15.0378 18.9108C13.9995 19.7293 12.9995 20.4999 11.9995 20.4999C10.9995 20.4999 9.99954 19.7293 8.96124 18.9108C8.88404 18.85 8.80614 18.7889 8.72754 18.7276");
}

</style>
