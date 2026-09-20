<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="oebw2zb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-all-28-filled" /></template>
<style>
.oebw2zb5p {
  fill: currentColor;
  d: path("M10.707 5.293a1 1 0 0 1 0 1.414L5.414 12l5.293 5.293a1 1 0 0 1-1.414 1.414l-6-6a1 1 0 0 1 0-1.414l6-6a1 1 0 0 1 1.414 0m5.5 0a1 1 0 0 1 0 1.414L11.914 11H15c5.523 0 10 4.477 10 10a1 1 0 1 1-2 0a8 8 0 0 0-8-8h-3.086l4.293 4.293a1 1 0 0 1-1.414 1.414l-6-6a1 1 0 0 1 0-1.414l6-6a1 1 0 0 1 1.414 0");
}

</style>
