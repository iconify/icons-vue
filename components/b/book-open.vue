<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_bfy4kya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open" /></template>
<style>
.v_bfy4kya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20V9a4 4 0 0 1 4-4h3a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-3c-.64 0-1.36.36-2 1zm0 0V9a4 4 0 0 0-4-4H5a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h3c.64 0 1.36.36 2 1z");
}

</style>
