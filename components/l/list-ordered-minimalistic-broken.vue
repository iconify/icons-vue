<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l7y12ieah"/><path class="v8tx6ieir"/><path class="a-d731ccj"/><path class="iw9omoj8x"/><path class="j6st1829s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-ordered-minimalistic-broken" /></template>
<style>
.a-d731ccj {
  d: path("M20 6L12 6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw9omoj8x {
  stroke-linejoin: round;
  d: path("M5.13477 6.5136L7.06207 5V9");
}

.j6st1829s {
  stroke-linejoin: round;
  d: path("M5.13477 14.0549C5.13477 13.4723 5.56616 13 6.0983 13C6.63045 13 7.06184 13.4723 7.06184 14.0549C7.06184 14.6375 6.8515 14.9177 6.47963 15.4326L5.13477 17H7.06184");
}

.l7y12ieah {
  d: path("M20 16H12");
}

.v8tx6ieir {
  d: path("M20 11L12 11");
}

</style>
