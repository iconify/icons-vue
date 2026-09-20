<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp6qgdbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-all-outline-rounded" /></template>
<style>
.pp6qgdbev {
  fill: currentColor;
  d: path("M3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21H5q-.825 0-1.412-.587T3 19m10-6v6h6v-6zm0-2h6V5h-6zm-2 0V5H5v6zm0 2H5v6h6z");
}

</style>
