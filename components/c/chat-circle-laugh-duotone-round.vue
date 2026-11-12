<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mx9hxde4b"/><path class="qlot2-bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-laugh-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mx9hxde4b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177Z");
}

.qlot2-bsy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Zm5-7h.01M15 9h.01M8 13a4 4 0 1 0 8 0Z");
}

</style>
