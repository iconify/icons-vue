<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o2yt9o3rn"/><path class="cv8ir4b7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:courthouse-duocolor-round" /></template>
<style>
.cv8ir4b7y {
  d: path("M12 7H3l9-4l9 4zM5 21v-3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v3M3 21h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2yt9o3rn {
  stroke-opacity: 0.4;
  d: path("M7 7v10m5-10v10m5-10v10");
}

</style>
