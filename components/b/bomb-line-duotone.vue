<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="uac092bgj"/><path class="d_hcm7xrk"/><path class="n8llc_q5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-line-duotone" /></template>
<style>
.d_hcm7xrk {
  d: path("M17 7L15 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8llc_q5p {
  d: path("M17.0124 4.32668L15.3532 4.98108C14.8823 5.16679 14.8823 5.83321 15.3532 6.01892L17.0124 6.67332C17.1562 6.73002 17.27 6.84382 17.3267 6.98758L17.9811 8.64684C18.1668 9.11772 18.8332 9.11772 19.0189 8.64684L19.6733 6.98758C19.73 6.84382 19.8438 6.73002 19.9876 6.67332L21.6468 6.01892C22.1177 5.83321 22.1177 5.16679 21.6468 4.98108L19.9876 4.32668C19.8438 4.26998 19.73 4.15618 19.6733 4.01242L19.0189 2.35316C18.8332 1.88228 18.1668 1.88228 17.9811 2.35316L17.3267 4.01242C17.27 4.15618 17.1562 4.26998 17.0124 4.32668Z");
}

.uac092bgj {
  cx: 9.5px;
  cy: 14.5px;
  r: 7.5px;
}

</style>
