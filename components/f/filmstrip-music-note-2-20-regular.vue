<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="quu7oobgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-music-note-2-20-regular" /></template>
<style>
.quu7oobgy {
  fill: currentColor;
  d: path("M17.09 5.018a.75.75 0 0 1 .91.732V15a2 2 0 1 1-1-1.73V8.61l-6 2.142V16a2 2 0 1 1-1-1.73v-6.2c0-.316.2-.6.498-.706l6.5-2.321zM9 15a1 1 0 1 0 0 2a1 1 0 0 0 0-2m7-1a1 1 0 1 0 0 2a1 1 0 0 0 0-2M11.5 2A2.5 2.5 0 0 1 14 4.5v.553l-1 .356V4.5A1.5 1.5 0 0 0 11.5 3h-7A1.5 1.5 0 0 0 3 4.5v6A1.5 1.5 0 0 0 4.5 12H9v1H4.5A2.5 2.5 0 0 1 2 10.5v-6A2.5 2.5 0 0 1 4.5 2zm-7 7.5a.5.5 0 0 1 .5.5v.5a.5.5 0 0 1-1 0V10a.5.5 0 0 1 .5-.5M11 8.247V9.69l6-2.142V6.104zM4.5 6.75a.5.5 0 0 1 .5.5v.5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 1 .5-.5M4.5 4a.5.5 0 0 1 .5.5V5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 1 .5-.5m7 0a.5.5 0 0 1 .5.5V5a.5.5 0 0 1-1 0v-.5a.5.5 0 0 1 .5-.5");
}

</style>
