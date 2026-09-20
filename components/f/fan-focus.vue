<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-_y-v4ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fan-focus" /></template>
<style>
.o-_y-v4ps {
  fill: currentColor;
  d: path("m12 22l-3.5-3.5l1.4-1.4l1.1 1.075V12h2v6.175l1.1-1.075l1.4 1.4zm-6-4l-3.5-3.5l1.4-1.4L5 14.175V8h2v6.175L8.1 13.1l1.4 1.4zm12 0l-3.5-3.5l1.4-1.4l1.1 1.075V8h2v6.175l1.1-1.075l1.4 1.4zM2 11V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v6h-2V5H4v6z");
}

</style>
