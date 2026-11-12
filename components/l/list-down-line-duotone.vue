<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ynnqgt8sp"/><path class="rhlnpmbpq"/><path class="mlijwm2tw"/><path class="k35jqkb4g"/><path class="tonplxqkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-down-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k35jqkb4g {
  d: path("M10 18H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mlijwm2tw {
  d: path("M10 14H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rhlnpmbpq {
  d: path("M21 10L3 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tonplxqkt {
  stroke-linejoin: round;
  d: path("M14 15L17.5 18L21 15");
}

.ynnqgt8sp {
  d: path("M21 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
