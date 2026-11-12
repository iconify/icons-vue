<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dzhqz82xf"/><path class="p8if-j44r"/><path class="z8asjk3rx"/><circle class="jx3h49bol"/><path class="d9v3nkbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-search-line-duotone" /></template>
<style>
.d9v3nkbry {
  d: path("M20.1213 19.8713L21.9999 21.75");
}

.dzhqz82xf {
  d: path("M22 13.75V11.75C22 7.97876 22 6.09315 20.8284 4.92157C19.6569 3.75 17.7712 3.75 14 3.75H10C6.22876 3.75 4.34315 3.75 3.17157 4.92157C2 6.09315 2 7.97876 2 11.75V13.75C2 17.5212 2 19.4069 3.17157 20.5784C4.34315 21.75 6.22876 21.75 10 21.75H14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jx3h49bol {
  cx: 18px;
  cy: 17.75px;
  r: 3px;
}

.p8if-j44r {
  d: path("M2.03516 8.75H21.965");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z8asjk3rx {
  d: path("M7 3.78496V2.25M17 3.78496V2.25");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
