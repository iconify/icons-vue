<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nbf8hob_w"/><circle class="gp0egaclj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:compass-big-line-duotone" /></template>
<style>
.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbf8hob_w {
  d: path("M14.7898 18.9746C16.132 18.4377 16.8031 18.1693 17.3295 17.7076C17.4637 17.59 17.59 17.4637 17.7076 17.3295C18.1693 16.8031 18.4377 16.132 18.9746 14.7898C21.4915 8.49749 22.75 5.35132 21.5288 3.55428C21.2393 3.1282 20.8718 2.7607 20.4457 2.47117C18.6487 1.25001 15.5025 2.50848 9.21017 5.02542C7.86802 5.56228 7.19695 5.8307 6.67048 6.29238C6.53633 6.41002 6.41002 6.53633 6.29238 6.67048C5.8307 7.19695 5.56228 7.86802 5.02542 9.21017C2.50848 15.5025 1.25001 18.6487 2.47117 20.4457C2.76071 20.8718 3.1282 21.2393 3.55428 21.5288C5.35132 22.75 8.49749 21.4915 14.7898 18.9746Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
