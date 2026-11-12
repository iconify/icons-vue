<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa-0euzqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pause-corner" /></template>
<style>
.pa-0euzqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-4 4v8m4-8v8");
}

</style>
