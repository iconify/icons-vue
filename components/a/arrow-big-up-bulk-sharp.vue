<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usdsqlbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-up-bulk-sharp" /></template>
<style>
.usdsqlbqd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 21H9a1 1 0 0 1-1-1v-7H4a1.002 1.002 0 0 1-.707-1.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 20 13h-4v7a1 1 0 0 1-1 1");
}

</style>
