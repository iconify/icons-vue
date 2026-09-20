<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lgym-9zis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-data-bar-32-filled" /></template>
<style>
.lgym-9zis {
  fill: currentColor;
  d: path("M19 22a2 2 0 0 1 2 2v5a2 2 0 1 1-4 0v-5a2 2 0 0 1 2-2m5-6a2 2 0 0 1 2 2v11a2 2 0 1 1-4 0V18a2 2 0 0 1 2-2m5 4a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0v-7a2 2 0 0 1 2-2m0-1.5c-.537 0-1.046.12-1.5.336V18a3.5 3.5 0 1 0-7 0v2.836a3.5 3.5 0 0 0-5 3.164v5h-8A4.5 4.5 0 0 1 3 24.5V11h26zM24.5 3A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
