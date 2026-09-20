<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e63f0-bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-mention-48-filled" /></template>
<style>
.e63f0-bly {
  fill: currentColor;
  d: path("M12 26c5.43 0 9.848 4.326 9.996 9.72L22 36v1.525a4 4 0 0 1-7.415 2.059c-.8.834-1.882 1.35-3.085 1.35c-2.515 0-4.5-2.25-4.5-4.967S8.985 31 11.5 31c.937 0 1.8.312 2.514.844a1 1 0 0 1 1.98.04L16 32v5.5a2 2 0 0 0 3.994.15l.006-.175V36a8 8 0 1 0-5.33 7.544a1 1 0 0 1 .667 1.886A10 10 0 0 1 12 46C6.477 46 2 41.523 2 36s4.477-10 10-10m12-10.75A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H19.283A6.5 6.5 0 0 0 24 37.75q-.001-.06-.004-.118L24 37.5V36c0-6.627-5.373-12-12-12a12 12 0 0 0-4 .686V7a3 3 0 0 1 3-3h13zM11.5 33C10.15 33 9 34.302 9 35.967c0 1.664 1.15 2.967 2.5 2.967c1.3 0 2.414-1.208 2.495-2.784l.005-.22c-.016-1.585-1.075-2.834-2.35-2.925zm27.962-16.5H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
