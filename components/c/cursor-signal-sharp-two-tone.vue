<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lo9uc9ynl"/><path class="nel6rabuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-signal-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lo9uc9ynl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.2883 10.8553L13.7332 21.6811C13.8594 22.0779 14.4083 22.1135 14.5851 21.7365L16.8571 16.8893C16.9055 16.7862 16.9907 16.7047 17.0961 16.661L21.7178 14.7424C22.1089 14.58 22.0887 14.0207 21.6869 13.8869L10.8703 10.2835C10.5149 10.1651 10.175 10.4991 10.2883 10.8553Z");
  stroke: none;
}

.nel6rabuy {
  d: path("M10.0158 9.9989L14.088 22L16.9324 16.7288L22 14.2735L10.0158 9.9989ZM6 11L6 10C6 7.7909 7.7909 6 10 6L11 6M2 11L2 10C2 5.5817 5.5817 2 10 2L11 2");
}

</style>
