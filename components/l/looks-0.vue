<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4numxbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-0" /></template>
<style>
.k4numxbds {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5h14v14H5zm6 12h2q.825 0 1.413-.587T15 15V9q0-.825-.587-1.412T13 7h-2q-.825 0-1.412.588T9 9v6q0 .825.588 1.413T11 17m0-8h2v6h-2z");
}

</style>
