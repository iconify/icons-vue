<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ulqic86jp"/><path class="mtt62ulyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:github-duocolor-round" /></template>
<style>
.mtt62ulyt {
  d: path("M9 21v-3c0-1 0-2 1-3c-3 0-6-2-6-6c0-1.3.5-2.3 1-3q-.6-1.5 0-3s1.5 0 4 1q3-.75 6 0c2.5-1 4-1 4-1q.6 1.5 0 3c.5.7 1 1.7 1 3c0 4-3 6-6 6c1 1 1 2 1 3v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ulqic86jp {
  stroke-opacity: 0.4;
  d: path("M9 19c-4 1-4-3-6-3");
}

</style>
