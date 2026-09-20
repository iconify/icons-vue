<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toncqob0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-rounded" /></template>
<style>
.toncqob0w {
  fill: currentColor;
  d: path("M2 21q-.425 0-.712-.288T1 20t.288-.712T2 19h20q.425 0 .713.288T23 20t-.288.713T22 21zm2-3q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v11q0 .825-.587 1.413T20 18z");
}

</style>
