<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="merdn0nze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hourglass-24-filled" /></template>
<style>
.merdn0nze {
  fill: currentColor;
  d: path("M17.25 4.5H6.75a.25.25 0 0 0-.25.25v.6A3.24 3.24 0 0 0 7.92 8L10 9.48c.42.278.77.65 1.02 1.089a2.8 2.8 0 0 1 0 2.862c-.25.438-.6.811-1.02 1.089L7.92 16a3.24 3.24 0 0 0-1.42 2.65v.6a.25.25 0 0 0 .25.25h10.5a.25.25 0 0 0 .25-.25v-.6A3.24 3.24 0 0 0 16.08 16L14 14.52a3.2 3.2 0 0 1-1.02-1.089a2.8 2.8 0 0 1 0-2.862c.25-.438.6-.811 1.02-1.089L16.08 8a3.24 3.24 0 0 0 1.42-2.65v-.6a.25.25 0 0 0-.25-.25");
}

</style>
