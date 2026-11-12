<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u0ck9yb3g"/><path class="un29iqbuk"/><path class="fuprorb1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-lock-broken" /></template>
<style>
.fuprorb1g {
  d: path("M12 12V14.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u0ck9yb3g {
  stroke-linejoin: round;
  d: path("M7.07161 18.9503C7.81454 19.5423 8.57318 20.0869 9.26556 20.6154C10.2 21.3285 11.1 22 12 22C12.9 22 13.8 21.3285 14.7344 20.6154C17.3825 18.5943 21 16.3364 21 12.0992C21 7.86196 16.0499 4.85701 12 8.93062C7.95014 4.85701 3 7.86196 3 12.0992C3 13.4078 3.34504 14.5276 3.9 15.51");
}

.un29iqbuk {
  d: path("M17 7C17 3.68629 15.0125 2 12 2C8.98754 2 7 3.68629 7 7");
}

</style>
