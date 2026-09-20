<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p1icq3z5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-bar-16-regular" /></template>
<style>
.p1icq3z5x {
  fill: currentColor;
  d: path("M10.5 12a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1zm2-9A2.5 2.5 0 0 1 15 5.5v3a2.5 2.5 0 0 1-2.5 2.5h-9a2.5 2.5 0 0 1-2.487-2.244L1 8.5v-3A2.5 2.5 0 0 1 3.5 3zm-9 1A1.5 1.5 0 0 0 2 5.5v3l.008.153A1.5 1.5 0 0 0 3.5 10h9A1.5 1.5 0 0 0 14 8.5v-3A1.5 1.5 0 0 0 12.5 4zM8 5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m0 1a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-4 .25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
