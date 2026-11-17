<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a3echzbsw"/><path class="nh03-69zu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-duotone-round" /></template>
<style>
.a3echzbsw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7 20l-1-1a4.24 4.24 0 0 1 0-6l6-6a4.242 4.242 0 1 1 6 6l-7 7Z");
}

.ft5dv1b6b {
  fill: none;
}

.nh03-69zu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l3-3a4.243 4.243 0 0 0-6-6l-3 3m2 10h10M9 10l6 6m-6-6l-3 3a4.243 4.243 0 0 0 0 6l1 1h4l4-4");
}

</style>
