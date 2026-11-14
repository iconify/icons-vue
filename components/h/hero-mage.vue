<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnsdfvbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hero-mage" /></template>
<style>
.lnsdfvbbx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.221 2.294q.386 1.349 1.735 1.735q.143.041.26.134q.117.092.19.223q.072.13.089.278t-.024.292q-.026.092-.075.174q-.048.083-.116.15q-.067.068-.15.116q-.082.049-.174.075q-1.217.348-1.65 1.48l3.685 7.831q5.259.711 5.259 3.218q0 3.5-10.25 3.5q-4.041 0-6.926-.835Q1.75 19.703 1.75 18q0-2.518 5.306-3.225l4.624-7.86q-.438-1.102-1.636-1.444q-.143-.041-.26-.134q-.117-.092-.19-.223q-.072-.13-.089-.278t.024-.292q.026-.092.075-.174q.048-.083.116-.15q.067-.068.15-.116q.082-.049.174-.075q1.349-.386 1.735-1.735q.041-.143.134-.26q.092-.117.223-.19q.13-.072.278-.089t.292.024q.092.026.174.075q.083.048.15.116q.068.067.116.15q.049.082.075.174M8.903 14.595Q10.312 14.5 12 14.5q1.78 0 3.25.105l-2.824-6z");
}

</style>
