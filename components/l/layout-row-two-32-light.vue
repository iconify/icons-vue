<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mgl85rtcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-32-light" /></template>
<style>
.mgl85rtcq {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zM7.5 4A3.5 3.5 0 0 0 4 7.5v8h24v-8A3.5 3.5 0 0 0 24.5 4zM28 16.5H4v8A3.5 3.5 0 0 0 7.5 28h17a3.5 3.5 0 0 0 3.5-3.5z");
}

</style>
