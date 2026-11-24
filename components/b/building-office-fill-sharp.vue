<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9uwgwg6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-fill-sharp" /></template>
<style>
.b9uwgwg6j {
  fill: currentColor;
  d: path("M15 22v-5a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v5H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1Zm-6-9V9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4 0V9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm-6 13v-4h2v4Z");
}

</style>
