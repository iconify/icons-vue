<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ud73q6bne"/><path class="b_y70sbsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-line-duotone" /></template>
<style>
.b_y70sbsx {
  d: path("M19.5 12H9.5C7.83333 12 4.5 13 4.5 17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ud73q6bne {
  stroke-linejoin: round;
  d: path("M14.5 7L19.5 12L14.5 17");
}

</style>
