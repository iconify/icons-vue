<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hjuar3b7p"/><path class="dtoolxbmj"/><path class="az_in-1oe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-2-broken" /></template>
<style>
.az_in-1oe {
  d: path("M9.83789 5.51236L10.5587 4.79151C12.9474 2.40283 16.8202 2.40283 19.2089 4.79151M18.4881 14.1625L19.2089 13.4417C20.4329 12.2177 21.0297 10.604 20.9993 9");
}

.dtoolxbmj {
  d: path("M9.83789 14.1625L14.163 9.8374");
}

.hjuar3b7p {
  d: path("M14.1625 18.4876L13.4417 19.2085C11.053 21.5972 7.18019 21.5972 4.79151 19.2085C2.40283 16.8198 2.40283 12.947 4.79151 10.5583L5.51236 9.83746");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
