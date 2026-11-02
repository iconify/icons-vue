<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmksrjkpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:columns-duocolor-round" /></template>
<style>
.kmksrjkpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Zm10 0a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Z");
}

</style>
