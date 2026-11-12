<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fflwcby7a"/><path class="giqbfv3yn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-line-duotone" /></template>
<style>
.fflwcby7a {
  d: path("M20 12H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.giqbfv3yn {
  d: path("M10 6L4 12L10 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
