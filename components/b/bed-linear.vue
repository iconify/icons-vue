<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n8zs0qb3h"/><path class="se3c9bcgw"/><path class="rvd7q59pv"/><path class="sb7v6-b6z"/><path class="lpln-2bzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bed-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpln-2bzl {
  d: path("M12 7V12");
}

.n8zs0qb3h {
  d: path("M19 20V18.5M5 20V18.5");
}

.rvd7q59pv {
  d: path("M21 12C21 8.22876 21 6.34315 19.8284 5.17157C18.6569 4 16.7712 4 13 4H11C7.22876 4 5.34315 4 4.17157 5.17157C3 6.34315 3 8.22876 3 12");
}

.sb7v6-b6z {
  d: path("M18.5 12V10.5C18.5 8.61438 18.5 7.67157 17.9142 7.08579C17.3284 6.5 16.3856 6.5 14.5 6.5H9.5C7.61438 6.5 6.67157 6.5 6.08579 7.08579C5.5 7.67157 5.5 8.61438 5.5 10.5V12");
}

.se3c9bcgw {
  d: path("M5 18H19C19.9319 18 20.3978 18 20.7654 17.8478C21.2554 17.6448 21.6448 17.2554 21.8478 16.7654C22 16.3978 22 15.9319 22 15C22 14.0681 22 13.6022 21.8478 13.2346C21.6448 12.7446 21.2554 12.3552 20.7654 12.1522C20.3978 12 19.9319 12 19 12H5C4.06812 12 3.60218 12 3.23463 12.1522C2.74458 12.3552 2.35523 12.7446 2.15224 13.2346C2 13.6022 2 14.0681 2 15C2 15.9319 2 16.3978 2.15224 16.7654C2.35523 17.2554 2.74458 17.6448 3.23463 17.8478C3.60218 18 4.06812 18 5 18Z");
}

</style>
