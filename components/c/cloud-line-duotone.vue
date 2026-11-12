<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l9il5701h"/><path class="r9s0-kbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9il5701h {
  d: path("M14.381 9.02722C14.9767 8.81912 15.6178 8.70589 16.2857 8.70589C16.9404 8.70589 17.5693 8.81468 18.1551 9.01498C20.393 9.78024 22 11.8811 22 14.3529C22 17.4717 19.4416 20 16.2857 20H6.28571C3.91878 20 2 18.1038 2 15.7647C2 13.4256 3.91878 11.5294 6.28571 11.5294C6.56983 11.5294 6.8475 11.5567 7.11616 11.6089C7.68058 11.7184 8.20528 11.9374 8.66667 12.2426");
}

.r9s0-kbwx {
  d: path("M7.11597 11.6089C6.88688 10.9978 6.76172 10.3369 6.76172 9.64706C6.76172 6.52827 9.32009 4 12.476 4C15.4157 4 17.8369 6.19371 18.1549 9.01498");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
