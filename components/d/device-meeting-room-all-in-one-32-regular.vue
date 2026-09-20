<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q1kvbxbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-32-regular" /></template>
<style>
.q1kvbxbsp {
  fill: currentColor;
  d: path("M16 8a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5-5A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zM5 24.5A2.5 2.5 0 0 0 7.5 27h17a2.5 2.5 0 0 0 2.5-2.5V22H5zM7.5 5A2.5 2.5 0 0 0 5 7.5V20h22V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
