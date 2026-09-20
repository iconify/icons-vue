<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d968765wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-lock-32-regular" /></template>
<style>
.d968765wz {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h8.626A4 4 0 0 1 16 28v-1H7.5A2.5 2.5 0 0 1 5 24.5V11h22v4a5 5 0 0 1 1.92 3.106l.08.02V7.5A4.5 4.5 0 0 0 24.5 3zM5 7.5A2.5 2.5 0 0 1 7.5 5h17A2.5 2.5 0 0 1 27 7.5V9H5zm15.5 12H20a2.5 2.5 0 0 0-2.5 2.5v6a2.5 2.5 0 0 0 2.5 2.5h8a2.5 2.5 0 0 0 2.5-2.5v-6a2.5 2.5 0 0 0-2.5-2.5h-.5V19a3.5 3.5 0 1 0-7 0zm2-.5a1.5 1.5 0 0 1 3 0v.5h-3zm3.5 6a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
