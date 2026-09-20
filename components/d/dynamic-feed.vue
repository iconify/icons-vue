<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va9fgcbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dynamic-feed" /></template>
<style>
.va9fgcbev {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19v-7h2v7h9v2zm4-4q-.825 0-1.412-.587T6 15V8h2v7h9v2zm4-4q-.825 0-1.412-.587T10 11V5q0-.825.588-1.412T12 3h8q.825 0 1.413.588T22 5v6q0 .825-.587 1.413T20 13zm0-2h8V7h-8z");
}

</style>
