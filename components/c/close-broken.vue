<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p9h4jybmo"/><path class="fdi87hbgw"/><path class="urwe8bb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:close-broken" /></template>
<style>
.fdi87hbgw {
  d: path("M12.0068 12L5.00684 19");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p9h4jybmo {
  d: path("M19.0068 5L15.5068 8.5");
}

.urwe8bb9z {
  d: path("M19 19L5 5");
}

</style>
