<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y9s618baa"/><path class="ez9x9wbch"/><path class="mkvh_1b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizonta-spacing-linear" /></template>
<style>
.ez9x9wbch {
  d: path("M21 2L21 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkvh_1b6g {
  d: path("M16 8V16C16 17.8856 16 18.8284 15.4142 19.4142C14.8284 20 13.8856 20 12 20C10.1144 20 9.17157 20 8.58579 19.4142C8 18.8284 8 17.8856 8 16L8 8C8 6.11438 8 5.17157 8.58579 4.58579C9.17157 4 10.1144 4 12 4C13.8856 4 14.8284 4 15.4142 4.58579C16 5.17157 16 6.11438 16 8Z");
}

.y9s618baa {
  d: path("M3 2L3 22");
}

</style>
