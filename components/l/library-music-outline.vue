<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4sdt8b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:library-music-outline" /></template>
<style>
.j4sdt8b7y {
  fill: currentColor;
  d: path("M12.5 15q1.05 0 1.775-.725T15 12.5V7h3V5h-4v5.5q-.325-.25-.7-.375T12.5 10q-1.05 0-1.775.725T10 12.5t.725 1.775T12.5 15M8 18q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm0-2h12V4H8zm-4 6q-.825 0-1.412-.587T2 20V6h2v14h14v2zM8 4v12z");
}

</style>
