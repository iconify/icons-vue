<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xtbju33sf"/><path class="gzuovjbor"/><path class="y-gfmr48b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images-sharp-two-tone" /></template>
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

.xtbju33sf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2L21 2C21.5523 2 22 2.4477 22 3L22 17C22 17.5523 21.5523 18 21 18L7 18C6.4477 18 6 17.5523 6 17L6 3C6 2.4477 6.4477 2 7 2Z");
  stroke: none;
}

.y-gfmr48b {
  fill: currentColor;
  d: path("M12 7C12 7.5523 11.5523 8 11 8C10.4477 8 10 7.5523 10 7C10 6.4477 10.4477 6 11 6C11.5523 6 12 6.4477 12 7Z");
  stroke: none;
}

</style>
