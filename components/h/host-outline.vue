<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4en7slmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:host-outline" /></template>
<style>
.p4en7slmk {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h5q.825 0 1.413.588T11 5v14q0 .825-.587 1.413T9 21zm11 0q-.825 0-1.412-.587T13 19V5q0-.825.588-1.412T15 3h5q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21zM4 19h5V5H4zm11 0h5V5h-5zM5 15h3v-2H5zm11 0h3v-2h-3zM5 12h3v-2H5zm11 0h3v-2h-3zM5 9h3V7H5zm11 0h3V7h-3zM4 19h5zm11 0h5z");
}

</style>
