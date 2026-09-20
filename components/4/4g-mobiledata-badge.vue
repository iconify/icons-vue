<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h95zug3pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4g-mobiledata-badge" /></template>
<style>
.h95zug3pb {
  fill: currentColor;
  d: path("M3 21q-.825 0-1.412-.587T1 19V5q0-.825.588-1.412T3 3h18q.825 0 1.413.588T23 5v14q0 .825-.587 1.413T21 21zm17-10h-3.5v2H18v2h-3V9h5q0-.825-.587-1.412T18 7h-3q-.825 0-1.412.588T13 9v6q0 .825.588 1.413T15 17h3q.825 0 1.413-.587T20 15zM8 17h2v-3h2v-2h-2V7H8v5H6V7H4v7h4z");
}

</style>
