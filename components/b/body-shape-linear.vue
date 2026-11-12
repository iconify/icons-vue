<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bqzynmr5r"/><path class="jz282xbza"/><path class="fqfwrtbff"/><path class="y_tq40zug"/><path class="jyqcg84cw"/><path class="a3m7hwbga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-linear" /></template>
<style>
.a3m7hwbga {
  d: path("M12 22C11.5 20.5 9 17.5 3 17.5");
}

.bqzynmr5r {
  stroke-linejoin: round;
  d: path("M20 2C20 2 18 6.68839 18 10.5714C18 11.8147 18.426 12.855 19 13.8912C19.6606 15.0836 20.5171 16.2704 21.1457 17.7543C21.6446 18.932 22 20.2968 22 22");
}

.fqfwrtbff {
  d: path("M6 13H18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jyqcg84cw {
  d: path("M12 22C12.5 20.5 15 17.5 21 17.5");
}

.jz282xbza {
  stroke-linejoin: round;
  d: path("M4 2C4 2 6 6.68839 6 10.5714C6 11.8147 5.57398 12.855 5.00001 13.8912C4.33945 15.0836 3.48291 16.2704 2.85426 17.7543C2.35537 18.932 2 20.2968 2 22");
}

.y_tq40zug {
  d: path("M6 11H18");
}

</style>
