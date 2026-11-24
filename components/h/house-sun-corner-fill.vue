<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8me-zbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun-corner-fill" /></template>
<style>
.c8me-zbdm {
  fill: currentColor;
  d: path("M17.714 9H10a.997.997 0 0 0-1 1v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l4.397 3.847A1.001 1.001 0 0 1 17.714 9M15.5 12.5V12a1 1 0 0 1 2 0v.5a1 1 0 0 1-2 0m-2.536 1.879l-.353-.354a.999.999 0 1 1 1.414-1.414l.354.353c.39.391.39 1.024 0 1.415c-.391.39-1.024.39-1.415 0m5.657-1.415l.354-.353a.999.999 0 1 1 1.414 1.414l-.353.354a1 1 0 0 1-1.415-1.415M14.5 16.5a2 2 0 1 1 3.999-.001a2 2 0 0 1-3.999.001m-2 1H12a1 1 0 0 1 0-2h.5a1 1 0 0 1 0 2m8-2h.5a1 1 0 0 1 0 2h-.5a1 1 0 0 1 0-2m-6.121 4.536l-.354.353a.999.999 0 1 1-1.414-1.414l.353-.354a1 1 0 0 1 1.415 1.415m5.657-1.415l.353.354a.999.999 0 1 1-1.414 1.414l-.354-.353a1 1 0 0 1 0-1.415a1 1 0 0 1 1.415 0M17.5 20.5v.5a1 1 0 0 1-2 0v-.5a1 1 0 0 1 2 0");
}

</style>
