<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a-uw1xbbx"/><path class="d_xn5l81p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-ordered-duocolor-round" /></template>
<style>
.a-uw1xbbx {
  stroke-opacity: 0.4;
  d: path("m4 6l2-2v6m-2 6a2 2 0 1 1 4 0l-4 4h4");
}

.d_xn5l81p {
  d: path("M12 7h8m-8 5h8m-8 5h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
