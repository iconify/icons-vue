<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ckhddnose"/><path class="ztulofeqi"/><path class="r5lvzac_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-lock-line-duotone" /></template>
<style>
.ckhddnose {
  d: path("M17 7C17 3.68629 15.0125 2 12 2C8.98754 2 7 3.68629 7 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5lvzac_c {
  stroke-linejoin: round;
  d: path("M9.26556 20.6154C6.61748 18.5943 3 16.3364 3 12.0992C3 7.86196 7.95014 4.85701 12 8.93062C16.0499 4.85701 21 7.86196 21 12.0992C21 16.3364 17.3825 18.5943 14.7344 20.6154C13.8 21.3285 12.9 22 12 22C11.1 22 10.2 21.3285 9.26556 20.6154Z");
}

.ztulofeqi {
  d: path("M12 12V14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
