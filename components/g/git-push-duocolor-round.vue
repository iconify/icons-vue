<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b3ze4j7ov"/><path class="nh40kqpwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-push-duocolor-round" /></template>
<style>
.b3ze4j7ov {
  stroke-opacity: 0.4;
  d: path("M12 16V3M9 6l3-3l3 3");
}

.nh40kqpwu {
  d: path("M10 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
