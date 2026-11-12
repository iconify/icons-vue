<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zxgfo-b_h"/><path class="dqoud86nz"/><path class="ktpncgb0v"/><path class="ecerw2bpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-transfer-broken" /></template>
<style>
.dqoud86nz {
  stroke-linejoin: round;
  d: path("M15.5 14V20M13.5 18L15.5 20L17.5 18M20 20V14M18 16L20 14L22 16");
}

.ecerw2bpo {
  d: path("M11 10L22 10M2 10L7 10");
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

.zxgfo-b_h {
  d: path("M14 4C17.7712 4 19.6569 4 20.8284 5.17157C21.8915 6.23467 21.99 7.8857 21.9991 11M10 4C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H11.5");
}

</style>
