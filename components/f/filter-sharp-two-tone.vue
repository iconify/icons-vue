<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uwt0q_bjd"/><path class="n8j3ytb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n8j3ytb6t {
  d: path("M3 3L21 3L14 11.5001L14 19L10 21L10 11.5001L3 3Z");
}

.uwt0q_bjd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.8451 2 22.3092 2.9833 21.7719 3.6357L15 11.8589L15 19C15 19.3788 14.786 19.725 14.4472 19.8944L10.4472 21.8944C9.7823 22.2269 9 21.7434 9 21L9 11.8589L2.2281 3.6357C1.6908 2.9833 2.1549 2 3 2Z");
  stroke: none;
}

</style>
