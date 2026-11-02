<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spmi9nu8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:kanban-fill" /></template>
<style>
.spmi9nu8k {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm7 9V7a1 1 0 0 0-2 0v7a1 1 0 0 0 2 0m4-3V7a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4-4a1 1 0 0 0-2 0v9a1 1 0 0 0 2 0Z");
}

</style>
