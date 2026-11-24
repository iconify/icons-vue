<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brfdgebkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-corner-sharp" /></template>
<style>
.brfdgebkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21H4V10l8-7l5.714 5M15 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-1 7c0-1.105 1.343-2 3-2s3 .895 3 2");
}

</style>
