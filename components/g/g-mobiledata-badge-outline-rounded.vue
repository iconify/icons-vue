<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh2kd1b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:g-mobiledata-badge-outline-rounded" /></template>
<style>
.hh2kd1b3d {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14zm5 12h4q.825 0 1.413-.587T16 15v-3q0-.425-.288-.712T15 11h-2q-.425 0-.712.288T12 12t.288.713T13 13h1v2h-4V9h6q0-.825-.587-1.412T14 7h-4q-.825 0-1.412.588T8 9v6q0 .825.588 1.413T10 17");
}

</style>
