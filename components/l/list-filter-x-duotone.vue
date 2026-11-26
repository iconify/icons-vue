<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbp9zjbwl"/><path class="s-ck0tdyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-filter-x-duotone" /></template>
<style>
.fbp9zjbwl {
  stroke-opacity: 0.4;
  d: path("M2 7H14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-ck0tdyz {
  d: path("M6 13H18M10 19H14M18 5L22 9M22 5L18 9");
}

</style>
