<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yshcjbced"/><path class="s3j__thdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-check-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3j__thdr {
  d: path("M16 17L18 19L22 15");
}

.yshcjbced {
  fill: currentColor;
  d: path("M5 3L19 3C21.2091 3 23 4.7909 23 7L23 10C23 10.5523 22.5523 11 22 11L16 11C14.3431 11 13 12.3431 13 14L13 20C13 20.5523 12.5523 21 12 21L5 21C2.7909 21 1 19.2091 1 17L1 7C1 4.7909 2.7909 3 5 3ZM3 8L3 10L21 10L21 8L3 8Z");
  stroke: none;
}

</style>
