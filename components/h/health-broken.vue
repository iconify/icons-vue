<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f1s09-5xg"/><path class="uwxgtltno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:health-broken" /></template>
<style>
.f1s09-5xg {
  d: path("M18.5 9.00002H16.5M16.5 9.00002L14.5 9.00002M16.5 9.00002L16.5 7M16.5 9.00002L16.5 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwxgtltno {
  stroke-linejoin: round;
  d: path("M3.29334 13.294C2.50729 11.9943 2 10.6424 2 9.3175C2 3.08748 7.50016 0.761498 12 5.57412C16.4998 0.761498 22 3.08748 22 9.31747C22 13.0468 17.9806 16.991 15.0383 19.3787C13.7063 20.4596 13.0403 21 12 21C10.9597 21 10.2937 20.4595 8.96175 19.3787L8.96173 19.3786C8.02863 18.6214 6.9872 17.7077 6 16.6939");
}

</style>
