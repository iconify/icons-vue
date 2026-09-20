<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqru_ugbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:exit-to-app-outline" /></template>
<style>
.vqru_ugbj {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19v-4h2v4h14V5H5v4H3V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm5.5-4l-1.4-1.45L11.65 13H3v-2h8.65L9.1 8.45L10.5 7l5 5z");
}

</style>
