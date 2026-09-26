<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gzuovjbor"/><path class="y-gfmr48b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gzuovjbor {
  d: path("M3 7L3 21L17 21M7 3L21 3L21 17L7 17L7 3ZM7 14L15 10.0001L21 13");
}

.y-gfmr48b {
  fill: currentColor;
  d: path("M12 7C12 7.5523 11.5523 8 11 8C10.4477 8 10 7.5523 10 7C10 6.4477 10.4477 6 11 6C11.5523 6 12 6.4477 12 7Z");
  stroke: none;
}

</style>
