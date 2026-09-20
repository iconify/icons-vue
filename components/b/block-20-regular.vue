<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="i2h57fmri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:block-20-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i2h57fmri {
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16zm0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14zM6.5 9.5h7a.5.5 0 0 1 .09.992l-.09.008h-7a.5.5 0 0 1-.09-.992L6.5 9.5h7h-7z");
  fill: currentColor;
}

</style>
