<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fzwtqbyaa"/><path class="wavchbbsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-network-sharp-fill" /></template>
<style>
.fzwtqbyaa {
  fill: currentColor;
  d: path("M12 1C15.2836 1 17.9962 3.43502 18.4355 6.59766C20.4718 7.02825 22 8.83553 22 11C22 13.4853 19.9853 15.5 17.5 15.5H6.5C4.01472 15.5 2 13.4853 2 11C2 8.83586 3.52769 7.0286 5.56348 6.59766C6.00279 3.43496 8.71637 1 12 1Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wavchbbsh {
  d: path("M12 14.5L12 18L12 19M14 20C14 21.1046 13.1046 22 12 22C10.8954 22 10 21.1046 10 20C10 18.8954 10.8954 18 12 18C13.1046 18 14 18.8954 14 20ZM5 20L6 20L10 20M14 20L18 20L19 20");
}

</style>
