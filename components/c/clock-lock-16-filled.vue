<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r520a2bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-lock-16-filled" /></template>
<style>
.r520a2bct {
  fill: currentColor;
  d: path("M8 15a7 7 0 1 0-6.965-7.711A3 3 0 0 1 6.5 9v.063A2 2 0 0 1 8 11zM8 4.5V8h2.5a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 1 0M1.5 9v1H1a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1h-.5V9a2 2 0 1 0-4 0m1 1V9a1 1 0 0 1 2 0v1zm1 2.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
