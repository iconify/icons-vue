<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjsut3bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ios-share" /></template>
<style>
.bjsut3bfn {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V10q0-.825.588-1.412T6 8h3v2H6v10h12V10h-3V8h3q.825 0 1.413.588T20 10v10q0 .825-.587 1.413T18 22zm5-6V4.825l-1.6 1.6L8 5l4-4l4 4l-1.4 1.425l-1.6-1.6V16z");
}

</style>
