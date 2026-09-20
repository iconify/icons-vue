<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsg2zuykm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-arrow-clockwise-24-regular" /></template>
<style>
.wsg2zuykm {
  fill: currentColor;
  d: path("M21.25 5a.75.75 0 0 0 .75-.75V1.5a.75.75 0 0 0-1.5 0v.626A6 6 0 1 0 23 7a.75.75 0 0 0-1.5 0a4.5 4.5 0 1 1-1.67-3.5H18.5a.75.75 0 0 0 0 1.5zM6.5 2h5.601a7 7 0 0 0-1.165 1.5H6.5a1 1 0 0 0-1 1V18H19v-4.29a7 7 0 0 0 1.5-.647v5.687a.75.75 0 0 1-.75.75H5.5a1 1 0 0 0 1 1h13.25a.75.75 0 0 1 0 1.5H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2");
}

</style>
