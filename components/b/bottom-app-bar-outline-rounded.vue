<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x74j1ccvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-app-bar-outline-rounded" /></template>
<style>
.x74j1ccvv {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-5v3h14v-3h-4.8q-.425.45-.987.725T12 17t-1.213-.275T9.8 16zm7.713-1.287Q13 14.425 13 14t-.288-.712T12 13t-.712.288T11 14t.288.713T12 15t.713-.288M5 14h4q0-1.25.875-2.125T12 11t2.125.875T15 14h4V5H5zm0 5h14z");
}

</style>
