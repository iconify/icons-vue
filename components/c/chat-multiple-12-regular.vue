<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v0iplca2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-multiple-12-regular" /></template>
<style>
.v0iplca2z {
  fill: currentColor;
  d: path("M9.95 4.299A4 4 0 0 1 11 7c0 .698-.18 1.355-.496 1.927l.47 1.415a.5.5 0 0 1-.632.633l-1.413-.472A4 4 0 0 1 7 11c-1.042 0-1.991-.4-2.703-1.053q.345.051.703.053q.583-.002 1.128-.13a3 3 0 0 0 2.477-.335a.5.5 0 0 1 .425-.053l.68.227l-.226-.68a.5.5 0 0 1 .052-.425a2.98 2.98 0 0 0 .334-2.475a5 5 0 0 0 .08-1.83M5 1a4 4 0 1 1-1.929 7.503l-1.413.472a.5.5 0 0 1-.632-.633l.47-1.415A4 4 0 0 1 5 1m0 1a3 3 0 0 0-2.536 4.604a.5.5 0 0 1 .053.425l-.227.68l.68-.227a.5.5 0 0 1 .426.053A3 3 0 1 0 5 2");
}

</style>
