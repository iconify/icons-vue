<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2i4jm0vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-free-outline-rounded" /></template>
<style>
.o2i4jm0vr {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19v-3q0-.425.288-.712T4 15t.713.288T5 16v3h3q.425 0 .713.288T9 20t-.288.713T8 21zm14 0h-3q-.425 0-.712-.288T15 20t.288-.712T16 19h3v-3q0-.425.288-.712T20 15t.713.288T21 16v3q0 .825-.587 1.413T19 21M3 8V5q0-.825.588-1.412T5 3h3q.425 0 .713.288T9 4t-.288.713T8 5H5v3q0 .425-.288.713T4 9t-.712-.288T3 8m16 0V5h-3q-.425 0-.712-.288T15 4t.288-.712T16 3h3q.825 0 1.413.588T21 5v3q0 .425-.288.713T20 9t-.712-.288T19 8");
}

</style>
