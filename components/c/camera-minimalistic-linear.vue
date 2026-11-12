<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="fr_tmn9fp"/><path class="ojb24aczm"/><path class="x4pob2bni"/><path class="bcpsrtbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-minimalistic-linear" /></template>
<style>
.bcpsrtbhb {
  d: path("M15 3H9");
}

.fr_tmn9fp {
  cx: 12px;
  cy: 13px;
  r: 3px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ojb24aczm {
  d: path("M14.0001 20H10.0001C7.19117 20 5.78671 20 4.77782 19.3259C4.34106 19.034 3.96605 18.659 3.67422 18.2223C3.0001 17.2134 3.0001 15.8089 3.0001 13L3.0001 12.9981C3.0001 10.1905 3.0001 8.78661 3.67407 7.77794C3.96591 7.34118 4.34091 6.96618 4.77767 6.67434C5.78656 6.00022 7.19103 6.00022 9.99995 6.00022H14C16.8089 6.00022 18.2133 6.00022 19.2222 6.67434C19.659 6.96618 20.034 7.34118 20.3258 7.77794C21 8.78683 21.0001 10.1911 21.0001 13C21.0001 15.8089 21.0001 17.2134 20.326 18.2223C20.0341 18.659 19.6591 19.034 19.2224 19.3259C18.2135 20 16.809 20 14.0001 20Z");
}

.x4pob2bni {
  d: path("M18 10H17.5");
}

</style>
