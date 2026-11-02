<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fprfyrbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-round" /></template>
<style>
.fprfyrbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17h10a2 2 0 0 0 2-2V7a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v12m2-2a2 2 0 1 0 0 4m0 0h6a4 4 0 0 0 4-4");
}

</style>
