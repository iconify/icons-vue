<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jp0olbbyo"/><path class="rj2y4vkzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airpods" /></template>
<style>
.jp0olbbyo {
  d: path("M7 3L17 3C19.7614 3 22 5.2386 22 8L22 16C22 18.7614 19.7614 21 17 21L7 21C4.2386 21 2 18.7614 2 16L2 8C2 5.2386 4.2386 3 7 3ZM2 9L22 9M9 8L15 8C15.5523 8 16 8.4477 16 9C16 9.5523 15.5523 10 15 10L9 10C8.4477 10 8 9.5523 8 9C8 8.4477 8.4477 8 9 8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rj2y4vkzd {
  fill: currentColor;
  d: path("M13 14C13 14.5523 12.5523 15 12 15C11.4477 15 11 14.5523 11 14C11 13.4477 11.4477 13 12 13C12.5523 13 13 13.4477 13 14Z");
  stroke: none;
}

</style>
