<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meeo48s9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hangout-video-off" /></template>
<style>
.meeo48s9t {
  fill: currentColor;
  d: path("M20.5 23.3L17.15 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l.6.6v2.8L.7 3.5l1.4-1.4l19.8 19.8zm1.25-4.4L18 15.15V8l-4 3.15v-3.1h-3.1L6.85 4H20q.825 0 1.413.588T22 6v12q0 .225-.062.45t-.188.45M6 16h7.15L6 8.85z");
}

</style>
