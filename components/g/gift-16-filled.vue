<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q4ok9gbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gift-16-filled" /></template>
<style>
.q4ok9gbid {
  fill: currentColor;
  d: path("M8 5H7v3H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h1.268A2 2 0 0 1 7.5 2.677A2 2 0 0 1 10.732 5H12a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1H8zM5 4a1 1 0 0 0 1 1h1V4a1 1 0 0 0-2 0m3 1h1a1 1 0 1 0-1-1zm4 4H8v5h2a2 2 0 0 0 2-2zm-5 5V9H3v3a2 2 0 0 0 2 2z");
}

</style>
