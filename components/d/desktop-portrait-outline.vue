<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mirpfnheu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-portrait-outline" /></template>
<style>
.mirpfnheu {
  fill: currentColor;
  d: path("M11 18h5V9h-5zm-3-3h1.5V7.5H13V6H8zm12 5q0 .825-.587 1.413T18 22H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4zm-2 0V4H6v16zm0-16H6z");
}

</style>
