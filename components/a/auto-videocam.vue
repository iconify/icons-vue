<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aleev4bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-videocam" /></template>
<style>
.aleev4bgj {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.413-.588T2 18V6q0-.825.588-1.413T4 4h12q.825 0 1.413.588T18 6v4.5l4-4v11l-4-4V18q0 .825-.588 1.413T16 20H4Zm6-4l1.25-2.75L14 12l-2.75-1.25L10 8l-1.25 2.75L6 12l2.75 1.25L10 16Z");
}

</style>
