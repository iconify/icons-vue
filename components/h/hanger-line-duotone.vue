<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aftxmccpa"/><path class="eu-wamb-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hanger-line-duotone" /></template>
<style>
.aftxmccpa {
  d: path("M3.70254 19H20.2975C21.9305 19 22.6234 17.1315 21.317 16.2509L13.8845 11.2405C13.2674 10.8246 12.533 10.6214 11.8015 10.6299C11.076 10.6383 10.3534 10.855 9.751 11.2787L2.65531 16.27C1.38322 17.1648 2.08721 19 3.70254 19Z");
}

.eu-wamb-b {
  d: path("M11.8017 10.6299V10.3455C11.8017 9.50197 12.695 8.84706 13.2928 8.19682C13.6049 7.85733 13.7841 7.40532 13.7841 6.90909C13.7841 5.85473 12.8332 5 11.6601 5C10.4871 5 9.53613 5.85473 9.53613 6.90909");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
