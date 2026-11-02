<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1qicxkof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:columns-bulk-round" /></template>
<style>
.f1qicxkof {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7a4 4 0 0 1 8 0v10a4 4 0 0 1-8 0Zm10 0a4 4 0 0 1 8 0v10a4 4 0 0 1-8 0Z");
}

</style>
