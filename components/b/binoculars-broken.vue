<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jsh7jib3y"/><path class="n7mec0bwr"/><path class="hf2jg-64g"/><path class="sqz4f0acc"/><path class="p_ni59b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-broken" /></template>
<style>
.hf2jg-64g {
  d: path("M14 15H10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsh7jib3y {
  d: path("M4.33466 6.02973L4.35032 5.98588C4.68171 5.05809 4.93283 4.35502 4.99982 4C5.23028 2.77865 5.49982 2 6.99982 2H8.73347C9.83804 2 9.99982 2.89543 9.99982 4V20C9.99982 21.1046 9.10439 22 7.99982 22H3.99982C2.89525 22 1.99982 21.1046 1.99982 20C1.99982 20 1.84202 16.9462 1.99982 15C2.13128 13.3787 2.53629 11.637 3.00869 10.0196");
}

.n7mec0bwr {
  d: path("M21.2718 11.0287C20.4247 7.80779 19.1637 4.86671 19.0002 4C18.7697 2.77865 18.5002 2 17.0002 2H15.2665C14.162 2 14.0002 2.89543 14.0002 4V20C14.0002 21.1046 14.8956 22 16.0002 22H20.0002C21.1047 22 22.0002 21.1046 22.0002 20C22.0002 20 22.158 16.9462 22.0002 15");
}

.p_ni59b0m {
  d: path("M14 9H10");
}

.sqz4f0acc {
  d: path("M9.99977 19H1.96045M22.0397 19H13.9943");
}

</style>
