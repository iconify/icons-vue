<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xd66job7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-circle-20-regular" /></template>
<style>
.xd66job7b {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14M7.81 7.114l.069.058L10 9.292l2.121-2.12a.5.5 0 0 1 .638-.058l.07.058a.5.5 0 0 1 .057.637l-.058.07L10.708 10l2.12 2.121a.5.5 0 0 1 .058.638l-.058.07a.5.5 0 0 1-.637.057l-.07-.058L10 10.708l-2.121 2.12a.5.5 0 0 1-.638.058l-.07-.058a.5.5 0 0 1-.057-.637l.058-.07L9.292 10l-2.12-2.121a.5.5 0 0 1-.058-.638l.058-.07a.5.5 0 0 1 .637-.057");
}

</style>
