<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kja0_8b-p"/><path class="hbv47lb9l"/><path class="fcaf33b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-line-duotone" /></template>
<style>
.fcaf33b7q {
  d: path("M6 15.5L11 12L6 8.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hbv47lb9l {
  d: path("M14.5253 20.5791L16.2633 19.3449C17.4211 18.5227 18 18.1116 18 17.5413C18 16.9709 17.4211 16.5598 16.2633 15.7376L11 12V18.7754C11 20.6618 11 21.605 11.6047 21.9144C12.2093 22.2238 12.9813 21.6755 14.5253 20.5791Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kja0_8b-p {
  d: path("M11 12L16.2633 8.26238C17.4211 7.44017 18 7.02907 18 6.45874C18 5.88842 17.4211 5.47731 16.2633 4.6551L14.5253 3.42093C12.9813 2.32448 12.2093 1.77625 11.6047 2.08561C11 2.39496 11 3.33816 11 5.22457V12Z");
}

</style>
