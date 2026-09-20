<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y53kr2b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-sliding-outline-rounded" /></template>
<style>
.y53kr2b4a {
  fill: currentColor;
  d: path("M8.288 12.713Q8 12.425 8 12t.288-.712T9 11t.713.288T10 12t-.288.713T9 13t-.712-.288m6 0Q14 12.426 14 12t.288-.712T15 11t.713.288T16 12t-.288.713T15 13t-.712-.288M4 21q-.425 0-.712-.288T3 20q0-.4.363-.562T4 19V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v14q.425 0 .713.288T21 20t-.288.713T20 21zm2-2h5V5H6zm7 0h5V5h-5zm-1-8");
}

</style>
