<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hiymv_bbi"/><path class="nof7dljmr"/><path clip-rule="evenodd" class="rlq3bc5ub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-alert-duotone" /></template>
<style>
.hiymv_bbi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3H19C21.2091 3 23 4.791 23 7V10C23 10.552 22.5523 11 22 11H16C14.3431 11 13 12.343 13 14V20C13 20.552 12.5523 21 12 21H5C2.7909 21 1 19.209 1 17V7C1 4.791 2.7909 3 5 3Z");
  stroke: none;
}

.nof7dljmr {
  d: path("M2 7L11.2929 11C11.7154 11.282 12.2846 11.282 12.7071 11L22 7M19 14V16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rlq3bc5ub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 20C20 20.552 19.5523 21 19 21C18.4477 21 18 20.552 18 20C18 19.448 18.4477 19 19 19C19.5523 19 20 19.448 20 20Z");
  stroke: none;
}

</style>
