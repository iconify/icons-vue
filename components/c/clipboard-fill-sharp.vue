<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff18h15nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-fill-sharp" /></template>
<style>
.ff18h15nn {
  fill: currentColor;
  d: path("M8 4V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v1h3a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1ZM6 6v14h12V6h-2v1a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V6Z");
}

</style>
