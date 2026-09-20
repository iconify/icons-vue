<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1g4_pupd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-2-20-regular" /></template>
<style>
.l1g4_pupd {
  fill: currentColor;
  d: path("M7.503 10a.5.5 0 0 1 .492.41l.008.09v5a.5.5 0 0 1-.992.09l-.008-.09v-5a.5.5 0 0 1 .5-.5M4.5 12a.5.5 0 0 1 .492.41L5 12.5v3a.5.5 0 0 1-.992.09L4 15.5v-3a.5.5 0 0 1 .5-.5m6-4.003a.5.5 0 0 1 .492.41l.008.09V15.5a.5.5 0 0 1-.992.09L10 15.5V8.497a.5.5 0 0 1 .5-.5m3-1.995a.5.5 0 0 1 .492.41l.008.09V15.5a.5.5 0 0 1-.992.09L13 15.5V6.502a.5.5 0 0 1 .5-.5");
}

</style>
