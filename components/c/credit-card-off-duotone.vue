<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nanb9e51p"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nanb9e51p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.563 20.683C20.083 20.887 19.555 21 19 21H5C2.791 21 1 19.209 1 17V7C1 5.41 1.928 4.036 3.272 3.392L7.88 8H3V10H9.88L20.563 20.683ZM14.243 10H21V8H12.243L8.95 4.707C8.769 4.526 8.657 4.276 8.657 4C8.657 3.448 9.105 3 9.657 3H19C21.209 3 23 4.791 23 7V16.343C23 16.895 22.552 17.343 22 17.343C21.724 17.343 21.474 17.231 21.293 17.05L14.243 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
