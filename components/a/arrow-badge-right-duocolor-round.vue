<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z51z7w07u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-right-duocolor-round" /></template>
<style>
.z51z7w07u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 19H6c-.738 0-1.369-.631-1-1l5-5a1.414 1.414 0 0 0 0-2L5 6c-.369-.369.262-1 1-1h6c.64 0 1.36.36 2 1l5 5a1.414 1.414 0 0 1 0 2l-5 5c-.64.64-1.36 1-2 1z");
}

</style>
