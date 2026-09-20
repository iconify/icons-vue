<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhdqe8u5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-arrow-up" /></template>
<style>
.mhdqe8u5k {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h8.8q-.4.675-.6 1.438T13 6q0 2.5 1.75 4.25T19 12q.525 0 1.025-.088T21 11.65V19q0 .825-.587 1.413T19 21zm1-4h12l-3.75-5l-3 4L9 13zm12-7V5.825L16.4 7.4L15 6l4-4l4 4l-1.4 1.4L20 5.825V10z");
}

</style>
