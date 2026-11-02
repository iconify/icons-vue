<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvm1h1n-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-bulk-sharp" /></template>
<style>
.mvm1h1n-w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m14.707 3.293l2 2a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a.997.997 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 0Zm-8 4l4 4a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l4-4a.997.997 0 0 1 1.414 0m12 0l4 4a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 0m-4 8l2 2a1 1 0 0 1 0 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l4-4a1 1 0 0 1 1.414 0Z");
}

</style>
