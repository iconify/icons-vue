<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leppjwita"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-down-bulk-sharp" /></template>
<style>
.leppjwita {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 13c0 .265-.105.52-.293.707l-7 7a1 1 0 0 1-1.414 0l-7-7A1 1 0 0 1 4 13V4a1.002 1.002 0 0 1 1.707-.707L12 9.586l6.293-6.293A1 1 0 0 1 20 4Z");
}

</style>
