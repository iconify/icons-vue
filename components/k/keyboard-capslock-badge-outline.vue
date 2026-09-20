<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf5st3b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-capslock-badge-outline" /></template>
<style>
.pf5st3b0l {
  fill: currentColor;
  d: path("M7 17h10v-2H7zm1.4-4L12 9.4l3.6 3.6l1.4-1.4l-5-5l-5 5zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
