<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2_wtg5el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ink-highlighter" /></template>
<style>
.y2_wtg5el {
  fill: currentColor;
  d: path("m10.292 10.385l4.016 4.015l-4.885 4.885q-.484.484-1.13.484q-.647 0-1.131-.484l-.204-.204l-1.15 1.15h-2.77l2.535-2.535l-.165-.165q-.485-.485-.485-1.131t.485-1.13zm.714-.714l4.956-4.955q.484-.485 1.13-.485q.647 0 1.131.485l1.754 1.753q.485.485.485 1.131t-.485 1.13l-4.956 4.957z");
}

</style>
