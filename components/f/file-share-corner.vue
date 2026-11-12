<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf87rdbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-share-corner" /></template>
<style>
.sf87rdbzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-3 5h4v4m0-4l-6 6");
}

</style>
