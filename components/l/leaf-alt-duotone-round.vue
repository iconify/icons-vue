<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="erfuebb9p"/><path class="g663zqz4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-alt-duotone-round" /></template>
<style>
.erfuebb9p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 19a1 1 0 0 1-.707-.293c-.924-.924-1.644-2.045-2.005-3.307C3.06 14.6 3 13.826 3 13c0-2.744.854-5.296 2.97-7.131C8.658 3.542 12.57 3.001 16 3h4a1 1 0 0 1 1 1v2l-.002.057c-.203 3.534-1.062 7.328-3.646 9.916C15.106 18.219 12.103 18.999 9 19Z");
}

.ft5dv1b6b {
  fill: none;
}

.g663zqz4y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 18c6.22 0 10.5-3.29 11-12V4h-4C7 4 4 8 4 13c0 1 0 3 2 5zm-4 3c.1-.7.4-1.8 1-3m0 0c1.5-3 3-6 6-7");
}

</style>
