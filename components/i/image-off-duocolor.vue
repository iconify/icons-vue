<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zf5-chd9w"/><path class="iwm20oage"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-duocolor" /></template>
<style>
.iwm20oage {
  d: path("M20.414 20.414A2 2 0 0 1 19 21H5a2 2 0 0 1-2-2V5c0-.552.224-1.052.586-1.414M9 3h10a2 2 0 0 1 2 2v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zf5-chd9w {
  stroke-opacity: 0.4;
  d: path("m3 17l7-7m6-3a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

</style>
