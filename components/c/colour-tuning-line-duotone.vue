<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a_fkomb0s"/><path class="uk8ks_p6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:colour-tuning-line-duotone" /></template>
<style>
.a_fkomb0s {
  d: path("M14.5 12H22M2 12H9.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uk8ks_p6o {
  d: path("M20.0002 15.6842C20.0002 19 17.7345 22 16.0002 22C13.7315 22 12.0723 18.8421 12.0723 12C12.0723 5.15791 10.4128 1.99985 8.14404 1.99985C6.40978 1.99985 4.14404 4.99985 4.14404 8.31564");
}

</style>
