<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty9cf6l2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-fill-sharp" /></template>
<style>
.ty9cf6l2t {
  fill: currentColor;
  d: path("M7 8V7a5 5 0 0 1 10 0v1h3a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1Zm8-1a3 3 0 1 0-6 0v1h6Zm-7 9v2a1 1 0 0 0 1 1h2c.265 0 .52-.105.707-.293l4-4a1 1 0 0 0 0-1.414l-2-2a1 1 0 0 0-1.414 0l-4 4A1 1 0 0 0 8 16");
}

</style>
