<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4kf3by-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-arrow-up" /></template>
<style>
.i4kf3by-d {
  fill: currentColor;
  d: path("M1 21v-2h22v2zm3-3q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v11q0 .825-.587 1.413T20 18zm7-3.5h2v-4.175l1.6 1.575l1.4-1.4l-4-4l-4 4l1.4 1.425l1.6-1.6z");
}

</style>
