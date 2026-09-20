<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hfo01lgmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contact-card-32-filled" /></template>
<style>
.hfo01lgmj {
  fill: currentColor;
  d: path("M5.25 4A3.25 3.25 0 0 0 2 7.25v17.5A3.25 3.25 0 0 0 5.25 28h21.5A3.25 3.25 0 0 0 30 24.75V7.25A3.25 3.25 0 0 0 26.75 4zM18 13a1 1 0 0 1 1-1h6a1 1 0 0 1 0 2h-6a1 1 0 0 1-1-1m1 4h6a1 1 0 0 1 0 2h-6a1 1 0 1 1 0-2m-6-4a2 2 0 1 1-4 0a2 2 0 0 1 4 0m-6 4.5A1.5 1.5 0 0 1 8.5 16h5a1.5 1.5 0 0 1 1.5 1.5s0 3.5-4 3.5s-4-3.5-4-3.5");
}

</style>
