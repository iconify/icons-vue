<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e118m9bhl"/><path class="wyaixbcry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bone-duotone-sharp" /></template>
<style>
.e118m9bhl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m10.707 17.707l-.01.011c.023.089.055.175.086.262c.117.33.217.666.217 1.02a3 3 0 1 1-6 0a3 3 0 1 1 0-6c.354 0 .69.1 1.02.217c.087.031.173.063.262.086l.011-.01l7-7l.01-.011c-.023-.089-.055-.175-.086-.262C13.1 5.69 13 5.354 13 5a3 3 0 1 1 6 0a3 3 0 1 1 0 6c-.354 0-.69-.1-1.02-.217c-.087-.031-.173-.063-.262-.086l-.011.01Z");
}

.ft5dv1b6b {
  fill: none;
}

.wyaixbcry {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 10c.7-.7 1.3 0 2 0a2 2 0 1 0 0-4a1 1 0 0 1-1-1a2 2 0 1 0-4 0c0 .7.7 1.3 0 2l-7 7c-.7.7-1.3 0-2 0a2 2 0 1 0 0 4a1 1 0 0 1 1 1a2 2 0 1 0 4 0c0-.7-.7-1.3 0-2Z");
}

</style>
