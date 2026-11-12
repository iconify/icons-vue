<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mr7muf4pj"/><path class="v7ab_1i9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mr7muf4pj {
  d: path("M4 11.9998L20 11.9998");
}

.v7ab_1i9x {
  d: path("M12.0204 3.99997L12.0205 20.0003");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
