<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e7djpjbfe"/><path class="ktpncgb0v"/><circle class="aaakgqotp"/><path class="i8e2akblu"/><path class="ecerw2bpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-search-broken" /></template>
<style>
.aaakgqotp {
  cx: 18px;
  cy: 17px;
  r: 3px;
}

.e7djpjbfe {
  d: path("M14 4C17.7712 4 19.6569 4 20.8284 5.17157C22 6.34315 22 8.22876 22 12V13M10 4C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H13");
}

.ecerw2bpo {
  d: path("M11 10L22 10M2 10L7 10");
}

.i8e2akblu {
  d: path("M20.5 19.5L21.5 20.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktpncgb0v {
  d: path("M10 16H6");
}

</style>
