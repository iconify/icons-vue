<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgdxg0bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-minus-corner-fill-sharp" /></template>
<style>
.mgdxg0bkd {
  fill: currentColor;
  d: path("M9 4h6V3a1 1 0 0 1 2 0v1h3a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5v10h4a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3V3a1 1 0 0 1 2 0Zm12 11a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
