<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z82veslhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-month-32-filled" /></template>
<style>
.z82veslhm {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zm9 5a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0M10.5 20a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m5.5 0a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m0-6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3m5.5 0a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
