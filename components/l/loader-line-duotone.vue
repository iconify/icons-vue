<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u0r4_lj8o"/><path class="its440yfc"/><path class="ujgww1per"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:loader-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.its440yfc {
  d: path("M2 12.0001C2 17.5229 6.47715 22.0001 12 22.0001C17.5228 22.0001 22 17.5229 22 12.0001C22 11.3187 21.9319 10.6533 21.802 10.0103");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.u0r4_lj8o {
  d: path("M14.0028 2.20061C13.3557 2.06906 12.6859 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12C22 11.3187 21.9319 10.6532 21.802 10.0102");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ujgww1per {
  d: path("M21.802 10.0103C21.9319 10.6533 22 11.3187 22 12.0001C22 17.5229 17.5228 22.0001 12 22.0001");
}

</style>
