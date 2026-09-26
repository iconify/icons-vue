<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hgrtmcj5y"/><path class="cqb5fwwed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cpu-sharp-fill" /></template>
<style>
.cqb5fwwed {
  d: path("M9 4L9 1M9 20L9 23M4 9L1 9M20 9L23 9M15 4L15 1M15 20L15 23M4 15L1 15M20 15L23 15");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hgrtmcj5y {
  fill: currentColor;
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 4C3 3.4477 3.4477 3 4 3ZM8 7C7.4477 7 7 7.4477 7 8L7 16C7 16.5523 7.4477 17 8 17L16 17C16.5523 17 17 16.5523 17 16L17 8C17 7.4477 16.5523 7 16 7L8 7Z");
  stroke: none;
}

</style>
