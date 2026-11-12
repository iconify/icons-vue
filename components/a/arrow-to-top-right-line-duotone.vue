<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u6_udqbqw"/><path class="zwy4hqbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-top-right-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6_udqbqw {
  stroke-linejoin: round;
  d: path("M7 9.5L12 4.5L17 9.5");
}

.zwy4hqbgn {
  d: path("M12 4.5L12 14.5C12 16.1667 13 19.5 17 19.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
