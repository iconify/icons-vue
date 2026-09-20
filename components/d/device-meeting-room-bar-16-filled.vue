<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e1s0imbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-bar-16-filled" /></template>
<style>
.e1s0imbqk {
  fill: currentColor;
  d: path("M10.5 12a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1zm2-9A2.5 2.5 0 0 1 15 5.5v3a2.5 2.5 0 0 1-2.5 2.5h-9a2.5 2.5 0 0 1-2.487-2.244L1 8.5v-3A2.5 2.5 0 0 1 3.5 3zM8 5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m0 1a1 1 0 1 1 0 2a1 1 0 0 1 0-2m-4.5.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
