<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c3f-hsbol"/><path class="alc4f-f5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:assistant-for-sv" /></template>
<style>
.alc4f-f5j {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M36.304 24c3.13-1.72 6.487-4.926 6.316-10.75c-4.958-3.06-9.413-1.756-12.468.095C30.227 9.773 29.129 5.263 24 2.5c-5.13 2.763-6.227 7.273-6.152 10.845c-3.055-1.851-7.51-3.156-12.468-.095c-.172 5.824 3.185 9.03 6.316 10.75c-3.13 1.72-6.488 4.926-6.316 10.75c4.958 3.06 9.413 1.757 12.468-.095C17.773 38.227 18.87 42.737 24 45.5c5.13-2.763 6.227-7.273 6.152-10.845c3.055 1.851 7.51 3.156 12.468.095c.172-5.824-3.185-9.03-6.316-10.75Z");
}

.c3f-hsbol {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
