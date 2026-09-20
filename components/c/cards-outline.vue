<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiz370y_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cards-outline" /></template>
<style>
.eiz370y_j {
  fill: currentColor;
  d: path("M6 11.5V6h5.5v5.5zM6 18v-5.5h5.5V18zm6.5-6.5V6H18v5.5zm0 6.5v-5.5H18V18zM8 9.5h1.5V8H8zm6.5 0H16V8h-1.5zM8 16h1.5v-1.5H8zm6.5 0H16v-1.5h-1.5zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5z");
}

</style>
