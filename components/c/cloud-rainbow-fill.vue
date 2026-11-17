<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="muifvbcnz"/><path class="yztaydb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rainbow-fill" /></template>
<style>
.muifvbcnz {
  fill: currentColor;
  d: path("M18 19C18 21.209 16.2092 23 14 23H5C2.7908 23 1 21.209 1 19C1 17.11 2.3105 15.527 4.0723 15.108C4.4983 12.495 6.766 10.5 9.5 10.5C12.2339 10.5 14.5006 12.495 14.9268 15.108C16.689 15.526 18 17.11 18 19Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yztaydb1y {
  d: path("M6.2146 8.16C7.0679 4.55 10.2907 2 14 2C18.4183 2 22 5.582 22 10V15M10.8013 7.598C11.5568 6.592 12.7417 6 14 6C16.2091 6 18 7.791 18 10V13.2");
}

</style>
