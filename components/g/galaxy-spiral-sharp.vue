<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tz1huc8oq"/><circle class="qcyv72b4r"/><path class="krnu5gb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:galaxy-spiral-sharp" /></template>
<style>
.krnu5gb9q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5h.01M19 19.5h.01");
}

.qcyv72b4r {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tz1huc8oq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.9 10.65l.76.702l.02.048l.252.593l-.202.677l-.263.842l-.667.738l-.83.899l-1.09.631l-1.355.767l-1.285.293l-1.591.38l-1.289-.13l-1.524-.152l-.986-.648l-.041-.028L3.37 14.42m5.73-1.07l-.76-.702l-.02-.048l-.252-.593l.202-.677l.263-.842l.667-.738l.83-.899l1.09-.631l1.355-.767l1.285-.293l1.591-.38l1.289.13l1.524.152l.986.648l.041.028L20.63 9.58");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
