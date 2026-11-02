<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ofpokoiuq"/><path class="jp7xb6-ci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eagle-duocolor" /></template>
<style>
.jp7xb6-ci {
  d: path("M8 6c2-2.3 4.8-3 7-3c3.5 0 6 2.5 6 6v11l-3-2l-2 3l-2-4l-3 3c0-2.5-.5-5-2-7H5c-.6 0-1 .4-1 1c-.7-.6-1-1.7-1-3c0-3 2-5 5-5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ofpokoiuq {
  stroke-opacity: 0.4;
  d: path("M12 9h.01");
}

</style>
