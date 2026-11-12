<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gy2469b1p"/><path class="u29udfb1o"/><path class="jgx5nz-xl"/><path class="r9gp_ab3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-vertical-line-duotone" /></template>
<style>
.gy2469b1p {
  d: path("M4 17H11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jgx5nz-xl {
  d: path("M4 7L11 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r9gp_ab3d {
  stroke-linejoin: round;
  d: path("M17 4L17 20M20 8L17 4L14 8M14 16L17 20L20 16");
}

.u29udfb1o {
  d: path("M4 12L11 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
