<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzvugsbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:app-shortcut-outline" /></template>
<style>
.fzvugsbay {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v4h-2V6H7v12h10v-1h2v4q0 .825-.587 1.413T17 23zm0-3v1h10v-1zM7 4h10V3H7zm0 0V3zm0 16v1zm10.15-7H12v3h-2v-3q0-.825.588-1.412T12 11h5.15L15.6 9.4L17 8l4 4l-4 4l-1.4-1.4z");
}

</style>
