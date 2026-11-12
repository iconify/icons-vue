<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zzd2qnarn"/><path class="b0469bblh"/><path class="dp6f7rbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chair-broken" /></template>
<style>
.b0469bblh {
  d: path("M11.9998 16H6.99977C6.01482 16 5.52235 16 5.22514 15.6762C4.92793 15.3523 4.96666 14.9018 5.0441 14.0008C5.10002 13.3503 5.22645 12.9125 5.51233 12.5858C6.02489 12 6.84985 12 8.49977 12H15.4998C17.1497 12 17.9746 12 18.4872 12.5858C18.7731 12.9125 18.8995 13.3503 18.9554 14.0008V14.0008C19.0329 14.9018 19.0716 15.3523 18.7744 15.6762C18.4772 16 17.9847 16 16.9998 16H15.9998");
}

.dp6f7rbss {
  d: path("M17 12V8C17 6.13077 17 5.19615 16.5981 4.5C16.3348 4.04394 15.9561 3.66523 15.5 3.40192C14.8038 3 13.8692 3 12 3C10.1308 3 9.19615 3 8.5 3.40192C8.04394 3.66523 7.66523 4.04394 7.40192 4.5C7 5.19615 7 6.13077 7 8V12H17Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzd2qnarn {
  d: path("M17 21V16M7 21V16");
}

</style>
