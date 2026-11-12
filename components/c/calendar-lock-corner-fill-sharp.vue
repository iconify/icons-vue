<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em1yy2jsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-lock-corner-fill-sharp" /></template>
<style>
.em1yy2jsi {
  fill: currentColor;
  d: path("M9 4h6V3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5v10h4a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3V3a1 1 0 0 1 2 0Zm12 11a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1h1a3 3 0 1 1 6 0Zm-3 0a1 1 0 0 0-2 0Zm-4 5h6v-3h-6Z");
}

</style>
