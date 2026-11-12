<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rsrhfac5n"/><path class="lht3z4o7e"/><path class="uwmybxzev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-off-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lht3z4o7e {
  d: path("M3.29916 20.7008C3 19.8314 3 18.3867 3 16.0909V11.0975C3 6.80891 3 4.6646 4.31802 3.3323C5.63604 2 7.75736 2 12 2C16.2426 2 18.364 2 19.682 3.3323C19.8485 3.50064 19.994 3.68194 20.1211 3.87889");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.uwmybxzev {
  d: path("M5.49902 21.9565C6.39205 21.7436 7.5139 20.7513 9.44213 19.0458L9.44214 19.0458C10.4612 18.1445 10.9707 17.6938 11.5603 17.5751C11.8506 17.5166 12.1494 17.5166 12.4397 17.5751C13.0292 17.6938 13.5388 18.1445 14.5578 19.0458L14.5579 19.0459C16.8633 21.0849 18.016 22.1045 19.0031 21.9915C19.4738 21.9377 19.9158 21.735 20.2659 21.4123C21 20.7358 21 19.1875 21 16.0909V11.0975C21 9.21023 21 7.7382 20.8877 6.5679");
}

</style>
