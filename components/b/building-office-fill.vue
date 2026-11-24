<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojflvcg5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-fill" /></template>
<style>
.ojflvcg5y {
  fill: currentColor;
  d: path("M15 22v-3a3 3 0 1 0-6 0v3H4a1 1 0 0 1-1-1V7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1Zm-6-9V9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4 0V9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm-6 13v-3a1 1 0 0 1 2 0v3Z");
}

</style>
