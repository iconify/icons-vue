<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xa_506f5h"/><path class="u-zqtib1a"/><path class="xvo0n--hd"/><path class="hjhjwb4fd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-up-minimalistic-linear" /></template>
<style>
.hjhjwb4fd {
  stroke-linejoin: round;
  d: path("M20 11.5L17.5 9L15 11.5M17.5 9V17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u-zqtib1a {
  d: path("M11 11L3 11");
}

.xa_506f5h {
  d: path("M20 6L3 6");
}

.xvo0n--hd {
  d: path("M12 16H3");
}

</style>
