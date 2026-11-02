<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w729gvbre"/><path class="a6mwcibor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:discord-duocolor-round" /></template>
<style>
.a6mwcibor {
  d: path("M8 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w729gvbre {
  stroke-opacity: 0.4;
  d: path("M12 6h2.03L15 4c1.5.16 3.04.49 4.43 1.5c1.57 5.67 1.67 9.83 1.17 11.45C20 18.33 18.86 20 17.33 20c-.5 0-2-2-2-3c-1.83.6-4.83.6-6.66 0c0 1-1.5 3-2 3C5.14 20 4 18.33 3.4 16.95C2.9 15.33 3 11.17 4.57 5.5C5.96 4.49 7.5 4.16 9 4l.97 2Z");
}

</style>
