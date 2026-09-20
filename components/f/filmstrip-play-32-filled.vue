<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="go1suvdod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-play-32-filled" /></template>
<style>
.go1suvdod {
  fill: currentColor;
  d: path("M6.5 4A4.5 4.5 0 0 0 2 8.5v15A4.5 4.5 0 0 0 6.5 28h19a4.5 4.5 0 0 0 4.5-4.5v-15A4.5 4.5 0 0 0 25.5 4zM26 8a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V9a1 1 0 0 1 1-1m-1 7a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zm1 5a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1M5 9a1 1 0 0 1 2 0v2a1 1 0 1 1-2 0zm1 5a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0v-2a1 1 0 0 1 1-1m-1 7a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zm8-7.95c0-.81.878-1.313 1.576-.905l5.6 3.272a.895.895 0 0 1 0 1.546l-5.6 3.272A1.048 1.048 0 0 1 13 19.331z");
}

</style>
