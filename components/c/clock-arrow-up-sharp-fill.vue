<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="i5kj9-bcx"/><path class="md27q_5nr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-arrow-up-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i5kj9-bcx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 13L13 13L13 22C13 22.5523 12.5523 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12C23 12.5523 22.5523 13 22 13ZM11 5L11 12C11 12.5523 11.4477 13 12 13L18 13L18 11L13 11L13 5L11 5Z");
  stroke: none;
}

.md27q_5nr {
  d: path("M19 23L19 16M22.2929 19.2929L19 16L15.7071 19.2929");
}

</style>
